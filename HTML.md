##### HTML

------



1. HTML的语义化理解：

- 让页面的内容结构化；
- 利于浏览器解析和SEO搜索引擎优化；
- 提高代码的可维护和可重用性；

2.div垂直居中的方法：

- 使用flex布局

  align-items:center

- 使用绝对定位

- 使用css3的transform属性

  ```
   position: relative;
   top: 50%; 
   transform: translateY(-50%)
  ```

1. position 几个属性的作用？

   - position 的常见四个属性值： relative，absolute，fixed，static。一般都要配合"left"、"top"、"right" 以及 "bottom" 属性使用。
   -  1）Static：默认位置，设置为 static 的元素，它始终会处于页面流给予的位置（static 元素会忽略任何 top、bottom、left 或 right 声明）。一般不常用。
   - 2）Relative：位置被设置为 relative 的元素，可将其移至相对于其正常位置的地方，意思就是如果设置了 relative 值，那么，它偏移的 top，right，bottom，left 的值都以它原来的位置为基准偏移，而不管其他元素会怎么样。注意 relative 移动后的元素在原来的位置仍占据空间。
   - 3）Absolute：位置设置为 absolute 的元素，可定位于相对于包含它的元素的指定坐标。意思就是如果它的父容器设置了 position 属性，并且 position 的属性值为 absolute 或者 relative，那么就会依据父容器进行偏 移。如果其父容器没有设置 position 属性，那么偏移是以 body 为依据。注
     意设置 absolute 属性的元素在标准流中不占位置。
   - 4）Fixed：位置被设置为 fixed 的元素，可定位于相对于浏览器窗口的指定坐标。不论窗口滚动与否，元素都会留在那个位置。它始终是以 body 为依据的。 注意设置 fixed 属性的元素在标准流中不占位置。
   
2. 清除浮动的方式：

   - 父级div定义height
   - 结尾处加空div标签 clear：both
   - 父级div定义伪类 ： after和zoom
   - 父级div定义overflow：hidden
   - 双伪元素法

3. display ：none 与 visibility: hidden 区别

   - display:none  使用该属性后，HTML元素的宽度、高度等各种属性值都将丢失；
   - visibility:hidden   使用后，它所占据的空间位置任然存在，它仍具有高度、宽度等属性值；

4. 行内元素，块级元素，空元素：

   - 行内元素： a b span img input select strong

   - 块级元素： div ul ol li dl dt dd h1 h2....p 

   - 空元素： 

     没有元素内容和标记的元素就成为空元素，也称自闭和元素

5. 单元格边距(cellpadding)    代表单元格外面的一个距离，用于隔开单元格与单元格空间

   元格间距(cellspacing )     代表表格边框与单元格补白的距离，也是单元格补白之间的距离

6. div和img之间有间隙的原因及解决办法

   - 因为img标签是行内标签，display：inline-block布局的元素在Chrome下会出现几像素的间隙，原因是因为我们在编辑器里写代码的时候，同级别的标签不写在同一行以保持代码的整齐可读性，即inline-block布局的元素在编辑器里不在同一行，即存在换行符，因此这就是著名的inline-block“换行符/空格间隙问题”
   - img{ display:block};（消除上下间隙）
   - img{vertical-align:top;}（消除上下间隙） 
   - div{ line-height:0 };（消除上下间隙） 
   - 多个标签写在一行（消除左右间隙） 
   - 使用letter-spacing属性（消除左右间隙） 
   - img{float: left;}（消除上下左右间隙 )
   - div{font-size:0};（消除上下左右间隙 ）

