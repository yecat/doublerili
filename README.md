# doublerili

#双日历#
双日历
为热热我热恶趣味
大苏打 大师傅大师傅发士大夫的

# 用法

      { $('#date').datePicker({
      monthsIn: 2, // 双日历
      max: new Date, // 最大日期 
      min: new Date,  // 最小日期,
      selected: new Date, // 默认选中日期
      range: true, // 是否开启范围选中
      onSelect: function(selectedDate) { // 选择日期后的回调函数
          
      }});}
      
      日期选择器，支持双日历，范围选择

依赖jquery, 模版引擎Juicer
