# 复选框
复选框取值 赋值 及全选



## jquery判断checkbox是否选中的方法:

.attr('checked'); //1.5-返回:true/false；1.6+返回:'checked' / 'undefined';

.prop('checked'); //16+:true/false;

.is(':checked'); //所有版本:true/false;



## jquery checkbox为赋值选中的写法:

.attr('checked','checked');

.attr('checked',true);

.prop('checked','checked');

.prop('checked',true);



## jquery中attr和prop的区别介绍：

•对于HTML元素本身就带有的固有属性，在处理时，使用prop方法。

•对于HTML元素我们自己自定义的DOM属性，在处理时，使用attr方法。


#### 这里$("#all").attr("checked") // undefined    $("#all").attr("checked") // "checked" (不推荐使用)

