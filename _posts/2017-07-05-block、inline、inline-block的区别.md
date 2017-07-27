---
layout: post
title:  block、inline、inline-block的区别
date:   2017-07-05 19:05:00 +0800
categories: 前端
tag: block
---

* content
{:toc}

之前一直不太清楚这三种属性值的具体区别，只是简单的认为块级元素的display值为block，所以每个块级元素都会自动换行，要想取消自动换行可以将display的值设置成inline就可以取消自动换行，但是没有仔细了解过它们三者，所以现在研究了一下。

### display:block
1、block元素会独占一行，宽度自动填满其父元素宽度。<br>
2、block元素可以设置width、height属性，块级元素即使设置了宽度仍然是独占一行。<br>
3、block元素可以设置margin和padding属性。

### display:inline
1、inline元素不会独占一行，一行排不下才会换新行，其宽度随内容的变化而变化。<br>
2、inline元素设置width、height属性无效。<br>
3、inline元素margin和padding水平方向能产生效果，竖直方向不会产生边距效果。

### display:inline-block
  将对象呈现为inline对象，但对象的内容作为block对象呈现，之后的內联对象会被排列在同一行内，将一个元素设置inline-block属性值，使其既具有block的宽度、高度特
性，又具有inline的同行特性。



常用块级元素：<br>
div, p ,form, ul, ol, li, ol, dl, form, address, fieldset, hr, menu, table
<br>
常用行内元素：<br>
span, strong, em, br, img, input, label,select,textarea,cite