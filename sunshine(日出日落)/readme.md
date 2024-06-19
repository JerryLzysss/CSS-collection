# 日出日落

采用原生HTML+CSS+JS.本来是想弄成类似于100daycss的day3效果.

原理:背景采用渐变色，原本是想弄成渐变背景的，不过linear-gradient不支持渐变，然后图形切割使用polygon函数进行截取，其他的就是单纯的animation移动。
polygon(0% 0%,50% 50%,0% 0%)=>表示的是截取内容中按照(x1 y1,x2 y2,x3 y3)的顺序依次截取。