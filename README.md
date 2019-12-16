# fcolorpicker
js colorpicker 颜色选择器


#使用
引用fcolorpicker.js后
初始化实例
var fcolorpicker = new FColorPicker({
        color: "red", selector: "#colorpicker",
        onError: function (e) {

        },
        onCancel:function(color){
            console.log("cancel",color)
        },
        onChange:function(color){
            console.log("change",color)
        },
        onConfirm:function(color){
            console.log("confirm",color)
        }
    })
    
#配置参数
showprecolor: true,//显示预制颜色
prevcolors: [
    '#EF534F', '#BA69C8', '#FFD54F', '#81C784','#7FDEEA','#90CAF9',
    '#F44436', '#AB47BC', '#FFC106', '#66BB6A','#25C6DA','#4EC3F7',
    '#E53934', '#9D27B0', '#FFA726', '#4CAF50','#00ACC1','#29B6F6',
    '#D32E30', '#8F24AA', '#FB8C01', '#378E3C','#0097A7','#02AAF4',
    '#C62928', '#7B1FA2', '#F57C02', '#2F7D31','#00838F','#029BE5',
    '#B71B1C', '#6A1B9A', '#EF6C00', '#34691D','#006164','#0388D1',
    '#980A0B', '#4A148C', '#E65100', '#1A5E20','#004D41','#01579B',
    '#FFFFFF', '#DBDBDB', '#C4C4C4', '#979797','#606060','#000000',
],//预制颜色
showhistorycolor: true,//显示历史
historycolornum: 16,//历史条数
format: 'hsla',//rgba hex hsla
showPalette:true,//显示色盘
show:true //初始化显示
    
    
