##### HTML

------



1. HTML的语义化理解：

- 让页面的内容结构化；
- 利于浏览器解析和SEO搜索引擎优化；
- 提高代码的可维护和可重用性；

2.怎么让一个不定宽高的 DIV，垂直水平居中？

- 使用 CSS 方法：
  父盒子设置：display：table-cell； text-align：center；vertical-align：middle；
  Div 设置： display：inline-block；vertical-align：middle；
- 使用 CSS3 transform：
  父盒子设置：display：relative
  Div 设置： transform： translate(-50%，-50%)；position： absolute；top： 50%；left：50%

1. position 几个属性的作用？

   - position 的常见四个属性值： relative，absolute，fixed，static。一般都要配合"left"、"top"、"right" 以及 "bottom" 属性使用。
   -  1）Static：默认位置，设置为 static 的元素，它始终会处于页面流给予的位置（static 元素会忽略任何 top、bottom、left 或 right 声明）。一般不常用。
   - 2）Relative：位置被设置为 relative 的元素，可将其移至相对于其正常位置的地方，意思就是如果设置了 relative 值，那么，它偏移的 top，right，bottom，left 的值都以它原来的位置为基准偏移，而不管其他元素会怎么样。注意 relative 移动后的元素在原来的位置仍占据空间。
   - 3）Absolute：位置设置为 absolute 的元素，可定位于相对于包含它的元素的指定坐标。意思就是如果它的父容器设置了 position 属性，并且 position 的属性值为 absolute 或者 relative，那么就会依据父容器进行偏移。如果其父容器没有设置 position 属性，那么偏移是以 body 为依据。注
     意设置 absolute 属性的元素在标准流中不占位置。
   - 4）Fixed：位置被设置为 fixed 的元素，可定位于相对于浏览器窗口的指定坐标。不论窗口滚动与否，元素都会留在那个位置。它始终是以 body 为依据的。 注意设置 fixed 属性的元素在标准流中不占位置。

