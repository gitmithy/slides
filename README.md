# slides
# 参数解释
jquery 轮播插件 目前只有一种特效 以后会慢慢完善<br>
container: 'slides_container',//包裹轮播元素class<br>
paginationClass: 'pagination',//分页<br>
speed:'350',//速度<br>
effect:'slide',//特效类型 fade渐隐 slide滑动<br>
currentClass: 'current',//分页当前class<br>
generateNextPrev: false,//是否生成下一页下一页<br>
generatePagination: true,//是否生成分页<br>
next: 'next',//下一页class<br>
prev: 'prev',//上一页class<br>
timeout:5000,//轮播时间<br>
auto: true//是否轮播<br>

# 用法
在需要轮播的外层直接调用slide然后传入参数 如<br>

$('#slides').slides(options);<br>

具体请看例子<br>