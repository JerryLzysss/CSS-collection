# Day7

## 效果:移动面板

### 做法:按部就班设计画面，过渡效果使用transition设置，然后唯一不同的是隐藏的设置，display:none是不显示，但是使用hover的时候会有显示，并且不支持过渡效果，visibility:hidden是隐藏内容，也不支持过渡效果，opacity:0是透明度，支持过渡效果，此处使用visibility+opacity来实现淡入淡出的效果，总体来说较为简单。

### 语言:LESS.推荐安装vscode的easy-less插件，引用的时候直接保存less便会生成css,如果配置网站的预加载器会导致加载缓慢。