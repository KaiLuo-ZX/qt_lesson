 来自wesbos 的javascript 30days ， 第一篇敲击乐，让我感受到html5模拟现实的强大魅力和创造力。 
  1. 构建音乐键盘
  	1.1 适配于所有设备的能力
    高度上 vh 相对单位 按比例来划分 100vh 是所有
    在不同大小的设备中，rem 可以无差别的来设置大小 
    1rem = html font-size 10px绝对单位 在PC时代是唯一
    相对单位 rem DOM树的树根  em 相对自己的font-size   移动互联网时代/5G时代
    .key  所有的大小设置都用相对单位  宽度， 高度（内容），
    圆角 边框 
    在不同的手机里， 10px 大小不一样
    请使用rem em vh vw 让页面适配所有设备
    1.2 使用移动互联网时代的布局方式
    弹性布局 display: flex;
    改变内部元素的原来的块级能力 display: block | inline 
    启动了display: flex 能力 
    对齐方式justify-content(主轴方向，默认水平，可以变化):
    center 
    align-items: center; (纵轴方向 )
    
   1.3 盒子模型 
   盒子在页面上占的大小 
   
 2. js 
 	html+css+js  
    js 是王者，  查找元素（html）， 设置属性 
    DOM API 
    document.getElementById(id)
    document.querySelectorAll(css selector)	
    document.querySelector(css selector)
    
    监听事件  keydown 事件名称 window 
    找到相应的元素， audio#id  DOMElement .play()  
  
 3. 逻辑部分， 如何按不同的键， 播放不同的声音呢？
 	if/else  switch/case 
 4. css  高级选择器
    audio[data-key="65"] 我们一般会为标签加一些data-数据属性，
    这个标签，它的数据是....
    	id  性能，查找时是很快，但要建索引  不用， 优化了网页性能
