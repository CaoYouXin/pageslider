# 纯CSS实现模块

ul.operations:

* 行高
* 行左右间距
* 行内可以有文本，图标，按钮，输入框，以及其它控件。

伪类的使用：

* 不变的东西可以写死在伪类里
* 变化的东西可以通过标签的自定义属性以及CSS属性值的attr函数引入伪类渲染
* 可惜attr与calc并不能混合使用，所以更多炫酷的写法留给未来的你

另外，让我发现CSS无比美丽的，是我之前写的打分器效果，使用如下属性：

* z-index
* margin-top负值
* transform 平移＋旋转
* transition-delay
* transition-timing-function
* transition-duration

聪明的你也许已经看出，CSS在渲染中的魅力。