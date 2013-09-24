---
layout: post
title: "[转]使用面向对象的技术创建高级 Web 应用程序"
category:前端
tags:[javaScript]
---
{% include JB/setup %}

##JavaScript 对象是词典

在 C++ 或 C# 中，在谈论对象时，是指类或结构的实例。对象有不同的属性和方法，具体取决于将它们实例化的模板（即类）。而 JavaScript 对象却不是这样。在 JavaScript 中，对象只是一组名称/值对，就是说，将 JavaScript 对象视为包含字符串关键字的词典。我们可以使用熟悉的“.”（点）运算符或“[]”运算符，来获得和设置对象的属性，这是在处理词典时通常采用的方法。以下代码段

var userObject = new Object();
userObject.lastLoginTime = new Date();
alert(userObject.lastLoginTime);  
