# Day13

## 效果:图片暗层+弹出效果

### 做法:最麻烦的一点不是在图片处理上，而是在触发js鼠标移入移出(模仿hover)的时候会出现内层元素也判断入内的情况，此处对移出事件进行了判断(说白了就是不影响原本内容的前提之下，不修改样式，没有根本改变鼠标移出的现象)，以及伸入时变黑的效果，就是通过再添加一层图层修改透明度来实现，主要还是不够熟悉js的使用导致卡壳了。

### 语言:LESS.推荐安装vscode的easy-less插件，引用的时候直接保存less便会生成css,如果配置网站的预加载器会导致加载缓慢。