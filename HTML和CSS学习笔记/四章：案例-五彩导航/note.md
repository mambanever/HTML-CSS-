# 第四章

## 一、emmet 语法使用

1. 快速生成 HTML 标签

2. 快速生成 CSS 样式
   属性的开头，

## 二、复合选择器

1. 后代选择器
   元素之间用空格隔开
   
   和类名结合使用，效果更佳
   
2. 子选择器
   使用 '>'表示元素的关系
   
   直接是所属的后代，也称为亲儿子选择器
   
3. 并集选择器
   用 ','表示元素的关系，
   
4. 伪类选择器
   链接伪类选择器的使用：用 ：表示
   - 四种样式：love 和 hate：link，visited，hover，active，且顺序不能改变
   
   focus 伪类选择器
   - 获取光标的元素
   - 主要应用在表单元素中，如 input：focus

## 三、元素显示模式

1. 块元素
   特点：独占一行，长宽高可设置，类似盒子
   
2. 行内元素

   特点：一行课显示多个元素，长宽设置无效，只能容纳内容和其他行内元素

   链接中不能再放链接

   特殊情况，可转换 a，在 a 标签中放入块元素

3. 行内块元素
   特点：一行课显示多个元素，长宽高可设置。
   
4. 显示模式转换：

   转块元素：display:block

   转行内元素：display:inline

   转行内块元素：display:inline-block

5. 单行文字垂直居中----行高和文字高度相等

## 四、CSS 的背景

1. 背景颜色：background-color

2. 背景图片：background-image
   多数应用在插入装饰的小图片，特大图片
   
   属性值：图片位置需要放 url()中
   
3. 背景平铺：background-repeat
   属性值：no-repeat,repeat-x,repeat-y
   
   背景颜色和图片可以叠加
   
4. 背景图片位置：background-position：x，y
   属性值：top，right，left，center
   
   也可以是像素，也可以混合单位，如 40px，center
   
5. 背景图片固定：background-attachment
   属性值：scroll 和 fixed
   
6. 背景复合写法：--顺序无关

7. 背景图片半透明：background：rgba(0,0,0,0.3)
