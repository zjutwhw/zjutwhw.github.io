---
layout: post
title: "Cocoa Touch 框架（一）"
date: 2016-03-10 10:03:22 +0800
comments: true
categories: iOS
---

> Cocoa Touch中众多框架中最重要最基本的两个框架是：`Foundation` 和 `UIKit`,其中`Foundation`与界面无关，包含一些最基本的类，而`UIKit`主要包含与界面相关的基础类。

![Cocoa框架](/images/cocoa_frame.jpg)

<!--more-->

****

**Foundation框架** 

*<图中灰色的是iOS不支持的，灰色部分是OS X系统的>*

![](/images/cocoa_foundation.png)

Foundation类组织架构可以按逻辑分类成如下：

+ 值对象
+ 集合 
+ 操作系统服务 
	* 文件系统
	* URL
	* 进程间通讯
+ 通知
+ 归档和序列化
+ 表达式和条件判断
+ Objective-C语言服务

**UIKit框架** 

![](/images/cocoa_uikit.jpg)

其中UIResponder是UIKit中非常重要的一个基类，也是图中最大的分支的根类，UIResponder为Cocoa Touch框架定义了事件响应链，UIKit生成事件通过UIResponder响应链来找到处理事件的对象。其中UIApplication，UIWindow，UIViewController，UIView都是继承至UIResponder，都有可能成为处理事件的对象。

**动态语言Object-C** 

Object-C是一门动态语言，相比其他语言(Java,C,C++)，它的动态特性主要表现如下三点：

+ 动态类：运行时确定类的对象 
+ 动态绑定：运行时确定要调用的方法
+ 动态加载：运行时为程序加载新的模块


