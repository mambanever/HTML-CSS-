# 第五章

## 一、CSS 三大特性

1. 层叠性
   主要解决样式冲突的问题
   
   遵循'就近原则',使用距离标签最近的 CSS
   
2. 继承性
   子标签继承父标签的样式
   
   行高的继承：倍数写法
   
3. 优先级
   由大到小：行内>id>类选择器>元素>继承和\*
   
   -----权重：1000>100>10>1>0

## 二、CSS 的权重叠加

1. CSS 样式权重大的会被使用，涉及权重的大小比较

## 三、盒子模型(三大页面布局核心之一：盒子模型，浮动，定位)

1. 页面的本质：用 CSS 设计和摆放各种盒子

2. 盒子模型的组成
   四部分：边框，外边距，内边距，实际内容
   
3. 边框：border
   属性：border-color，border-width，border-style
   
   style 属性值： solid 实线，dashed 虚线，dotted 点线
   
   复合写法：没有顺序要求
   
   针对上边框，下边框等的写法：border-top,border-bottom
   
4. 表格中相邻边框合并在一起：border-collapse：collapse

5. 边框影响会盒子的大小

6. 内边距：padding
   属性和边框差不多一样
   
   属性简写方式：1 个，2 个，3 个，4 个值对应的不同含义
   
   内边距也会影响盒子的大小
   
   如何盒子本身没有指定 width/height 属性，则 padding 不会撑开盒子
   
7. 外边距：margin
   简写和 padding 一样
   
   外边距让盒子居中：
   - 块级元素：设置宽度，左右 margin 设置 auto。比如:0 auto;
   - 盒子里行内元素：在父类元素中设置：text-align:center
   
   * 块元素嵌套合并塌陷问题：1.设置 border 2.设置 padding-top，3.overflow：hidden
   
8. 清除内外边距
   原因：元素自带默认的内外边距
   
   maigin 和 padding==0，即可
   
   行内元素不要设置上下内外边距

## 四、圆角边框(CSS3之后新增)
1. border-radius：r
   原理：圆的半径r

## 五、盒子阴影(CSS3之后新增)
1. box-shadow：x,y,blur,spread,color,inset(默认是外阴影)
   hover可以应用在其他标签上。
   
2. 文字阴影
