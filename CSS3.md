##### CSS3

------

1. css3新特性：

   - 过渡 transition
   - 动画 animation
   - 转换 transform
   - 阴影 box-shadow
   - 边框 border-image
   - 背景 background-clip
   - 颜色 rgba
   - filter(滤镜)
   - 弹性布局 flex
   - 盒模型定义 box-sizing
   - 媒体查询
2. css3选择器：

   - 属性选择器 如：[href = "a.mp4"]{color:green}
   - 伪类选择器 如 li:nth-child(2) {color:red}    li:nth-last-child(3){color:blue} 
   - 伪元素选择器 如 p::selection   p::first-line  li::first-letter   ::after  ::before
3. css3的兼容性问题怎么处理：

   - 一般加私有前缀否则不做特殊处理，并且遵循2大原则，渐进增强和优雅降级
4. 关于css3  calc()方法

   - calc是css3新增的一个功能，用来指定元素的长度，还可以用在流式布局上，可以通过calc()计算得到元素的宽度
   - 可以给一个div,使用百分比、em、px、和rem单位值计算出其宽度或高度，比如：width：calc(50% + 2em)   ,就可以直接计算出；
   - 运算符前后加空格；
   - 兼容性，在使用时需要加上标识符,移动端的浏览器不兼容
   - ` .elm {
     /*Firefox*/
       	-moz-calc(expression);
       	/*chrome safari*/
       	-webkit-calc(expression);
       	/*Standard */
       	calc();
     }`
5. less与sass

   - less与sass都是css预编译器，对css赋予了动态语言的特性；
   - sass的安装需要Ruby环境，是在服务器端处理的，而less是需要引入less.js来处理less代码比输出css到浏览器；
   - less的变量符是@  sass的变量符是$
   - less不支持条件控制语句

























