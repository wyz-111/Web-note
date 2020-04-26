##### css

------

1. css选择器，优先级：

   - ！important > 行内样式 > id >类 > 标签|伪类|属性选择 > 伪对象 > 继承 > 通配符

2. css预处理器:

   - less，sass
   - 结构清晰，便于扩展。
   - 可以方便的屏蔽浏览器私有语法差异。
   - 可以轻松实现多重继承。
   - 完全兼容css代码，可以方便的应用到老项目中

3. 行内元素，块级元素，空元素：

   - 行内元素： a b span img input select strong

   - 块级元素： div ul ol li dl dt dd h1 h2....p 

   - 空元素： 

     没有元素内容和标记的元素就成为空元素，也称自闭和元素

4. css中属性继承：

   - 所有元素可继承：visibility  和 cursor(光标属性)
   - 常见可继承：font-size、color、font-family、text-indent 、text-align...
   - 不可继承： border 、 margin、  padding、  display、background、height、width、overflow、position、left(等)、z-index、vertical-align...

5. css设置文字超出部分显示...的属性

   - white-space: nowrap;
   - text-overflow:ellipsis;

6. 

   - img{ display:block};（消除上下间隙）
   - img{vertical-align:top;}（消除上下间隙） 
   - div{ line-height:0 };（消除上下间隙） 
   - 多个标签写在一行（消除左右间隙） 
   - 使用letter-spacing属性（消除左右间隙） 
   - img{float: left;}（消除上下左右间隙 )
   - div{font-size:0};（消除上下左右间隙 )