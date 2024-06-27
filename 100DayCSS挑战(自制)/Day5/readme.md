# Day5

## 效果:模拟图表

### 做法:照本宣科，整个画面大差不大，就是曲线上比较折磨，以及效果原型图的做法是通过CSS直接写（不会),所以选择了用JS来触发，校对坐标真的很折磨，注意使用元素的PX（e.client获得的是窗口...踩坑了),然后就是曲线的生成是通过polyline,polyline的参数为:{points:"x1,y1 x2,y2 x3,y3"表示路径,stroke:blue表示边框颜色，fill:none表示填充,stroke-width表示边框宽度}