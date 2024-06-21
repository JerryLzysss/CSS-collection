# Day2

## 效果:三个长方形折叠动画

### 做法:依靠于animation提供的方法,第一个长方形先下移(transitionY)再旋转(rotate),第二个长方形缩放(scale),第三个长方形先上移(transitionZ)再旋转(rotate)即可完成。

### 一些心得:js中的css样式修改：对于获取css的样式，使用window.getComputedStyle(element.style)最为有效，而element.style则只能获得行内样式。