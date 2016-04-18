---
layout: post
title: "iOS调试工具初探"
date: 2016-04-18 16:47:32 +0800
comments: true
categories: iOS
---

**LLDB**

> LLDB是LLVM下的调试器，从Xcode5.0开始apple就开始将原来的gdb改为LLDB了，为所有的工程自动设置LLDB进行调试。本文总结下日常开发中使用到的一些LLDB命令，并如何使用Facebook开源的LLDB插件Chisel进行调试，提高我们开发过程中的开发效率。




参考：

+ [LLDB & GDB 内置命令对比](http://blog.163.com/l1_jun/blog/static/14386388201210202355254/)
+ [LLDB调试命令初探](http://www.starfelix.com/blog/2014/03/17/lldbdiao-shi-ming-ling-chu-tan/)
+ [Chisel-LLDB命令插件，让调试更Easy](https://blog.cnbluebox.com/blog/2015/03/05/chisel/)
+ [Chisel](https://github.com/facebook/chisel)



