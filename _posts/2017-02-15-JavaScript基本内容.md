---
layout: post
title:  JavaScript基本内容
date:   2017-02-15 01:08:00 +0800
categories: 前端
tag: JS
---

* content
{:toc}


JavaScript与ECMAScript
====================================
1、由于Netscape Navigator中的JavaScript与IE中的JScript同时存在，为了统一标准，1997年，欧洲计算机制造商协会完成了ECMA-262——一种名为ECMAScript的新脚本语言的标准。ECMAScript是JavaScript的核心，JavaScript由ECMAScript+Dom+Bom组成。
<br>
2、JavaScript由ECMAScript+Dom+Bom组成，Dom主要实现对HTML内部元素的操作，Bom主要实现对浏览器的操作。



script六大属性
====================================
（1）async:表示应该立即下载脚本，不妨碍页面其他操作。<br>
（2）defer:脚本可以延迟到其他文档完全被解析和显示之后再执行<br>
（3）charset:表示通过src属性指定的代码的字符集<br>
（4）src:表示包含要执行代码的外部文件<br>
（5）language:原来用来表示编写代码使用的脚本语言，已废弃<br>
（6）type:可以看成是language的替代属性，表示编写代码使用的脚本语言的内容类型


