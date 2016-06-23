# iOS Learning

iOS学习资源整理，包含一些开源组件和博客文章。

### 目录

- [基础](#基础)
- [控件](#控件)
  - [UIButton](#uibutton) 
  - [UITableView](#uitableview)
  - [UINavigationBar](#uinavigationbar)
  - [UICollectionView](#uicollectionview)
  - [UIResponder](#uiresponder)
  - [Slider](#slider)
  - [WebBrowser](#webbrowser)
  - [Chart-图表控件](#chart-图表控件)
    - [K线图](#k线图)
- [框架](#框架)
  - [AVFoundation](#avfoundation)
  - [Quick Look Framework](#quick-look-framework)
  - [Quartz 2D](#quartz-2d)
  - [ResearchKit](#researchkit)
- [动画](#动画)
  - [开源的动画框架](#开源的动画框架)
    - [pop](#pop)
  - [介绍动画的博文](#介绍动画的博文)
- [并发-多线程](#并发-多线程)
  - [GCD](#gcd)
- [Runtime](#runtime)
- [Category](#category)
  - [UIImage](#uiimage)
- [性能优化](#性能优化)
- [设计模式](#设计模式)
  - [类簇](#类簇)
  - [MVVM](#mvvm)
- [架构设计](#架构设计)
- [网络编程](#网络编程)
- [重构](#重构)
- [持续集成](#持续集成)
- [Git教程](#git教程)
- [书籍](#书籍)
- [工具](#工具)
  - [Xcode插件](#xcode插件)
  - [Cocoapods](#cocoapods)
  - [Hexo个人博客](#hexo个人博客)
  - [Markdown](#markdown)
    - [在线编辑器](#在线编辑器)
    - [语法](语法)
  
  
***

# 基础

* [instancetype 与 id for Objective-C](http://blog.csdn.net/wzzvictory/article/details/16994913)

# 控件

## UIButton
* [LCUIKit](https://github.com/lianchengjiang/LCUIKit) - 可以设置`UIButton`的*Text*和*Image*的相对位置，如上下左右等。
* [UIButton 的 imageEdgeInsets 和 titleEdgeInsets](http://www.jianshu.com/p/62850b201049)

## UITableView

* [Protocol Oriented UITableViewCells](http://bizz84.github.io/2016/06/18/Protocol-Oriented-UITableViewCells.html?utm_content=buffer05450&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer&utm_source=sendy&utm_medium=email&utm_campaign=sticker-pack)

## UINavigationBar

* [TLYShyNavBar](https://github.com/telly/TLYShyNavBar) - Unlike all those arrogant UINavigationBar, this one is shy and humble! Easily create auto-scrolling navigation bars! （ScorllView滚动时，自动隐藏和显示UINavigationBar）

## UICollectionView

* [UICollectionView 使用 介绍](http://blog.csdn.net/sqc3375177/article/details/17218455)
* [WWDC 2012 Session笔记——205 Introducing Collection Views](https://onevcat.com/2012/06/introducing-collection-views/)
* [WWDC 2012 Session笔记——219 Advanced Collection Views and Building Custom Layouts](https://onevcat.com/2012/08/advanced-collection-view/)

拖拽排序功能实现：
* [通过layout实现可拖拽自动排序的UICollectionView](http://www.jianshu.com/p/8d1bf1838882) - 英文[原文](http://blog.karmadust.com/drag-and-rearrange-uicollectionviews-through-layouts/)
* [http://nshint.io/blog/2015/07/16/uicollectionviews-now-have-easy-reordering/](http://nshint.io/blog/2015/07/16/uicollectionviews-now-have-easy-reordering/)
* [LXReorderableCollectionViewFlowLayout](https://github.com/lxcid/LXReorderableCollectionViewFlowLayout) - Extends `UICollectionViewFlowLayout` to support reordering of cells. Similar to long press and pan on books in iBook.
* [LewReorderableLayout](https://github.com/pljhonglu/LewReorderableLayout) - 一个 UICollectionViewLayout，长按可以拖拽排序，同时支持纵向和横线滚动。

## UIResponder

* [史上最详细的iOS之事件的传递和响应机制](http://www.cnblogs.com/machao/p/5471094.html)

## Slider

* [TTRangeSlider](https://github.com/TomThorpe/TTRangeSlider) - A slider, similar in style to UISlider, but which allows you to pick a minimum and maximum range.

## WebBrowser

* [KINWebBrowser](https://github.com/dfmuir/KINWebBrowser) - KINWebBrowser is a web browser module for your apps. Powered by WKWebView on iOS 8. Backwards compatible with iOS 7 using UIWebView.

## Chart-图表控件

* [iOS-Chats](https://github.com/danielgindi/Charts) -  Beautiful charts for iOS/tvOS/OSX! The Apple side of the crossplatform MPAndroidChart. 

### K线图

* [YKLineChartView](https://github.com/chenyk0317/YKLineChartView) - iOS 股票的K线图 分时图。
* [Cocoa-Charts](https://github.com/limccn/Cocoa-Charts) - Open-source iPhone/iPad graph/chart framework includes line chart,stick chart,candlestick chart,pie chart,spider-web chart etc. Based on iOS graph SDK, Using native Objective-c Codes.
* [BBStockChartView](https://github.com/chenxiaoyu3/BBStockChartView) - An iOS stock chart view, K-Line, volume Line.
* [KlineInSwift](https://github.com/mengmanzbh/KlineInSwift) - 用swift写的K线图
* [Y_KLine](https://github.com/yate1996/Y_KLine)

# 框架

## AVFoundation
* [iOS视频边下边播](http://www.jianshu.com/p/990ee3db0563) - iOS视频边下边播--缓存播放数据流

## Quick Look Framework

* [使用Quick Look框架对文件进行预览](https://segmentfault.com/a/1190000005010273) - 英文原文链接：[http://www.appcoda.com/quick-look-framework/](http://www.appcoda.com/quick-look-framework/)

## Quartz 2D

* [Quartz 2D Programming Guide](https://developer.apple.com/library/ios/documentation/GraphicsImaging/Conceptual/drawingwithquartz2d/Introduction/Introduction.html) - 官方教程
* [Quartz 2D编程指南之一：概览](http://southpeak.github.io/blog/2014/11/10/quartz-2dbian-cheng-zhi-nan-zhi-%5B%3F%5D-:gai-lan/) - 南峰子对[Quartz 2D Programming Guide](https://developer.apple.com/library/ios/documentation/GraphicsImaging/Conceptual/drawingwithquartz2d/Introduction/Introduction.html)的译文，值得推荐。
* [Graphing with Quartz 2D](http://www.sitepoint.com/series/graphing-with-quartz-2d/) - 几个Demo.
* [An Introduction to Quartz 2D](http://code.tutsplus.com/tutorials/an-introduction-to-quartz-2d--cms-24267)
* [Quartz2D 编程指南（一）概览、图形上下文、路径、颜色与颜色空间 ](http://www.jianshu.com/p/eb6bd4b0f9a5) - 本篇博客主要是对官方文档的总结与补充

## ResearchKit

* [ResearchKit](https://github.com/ResearchKit/ResearchKit) - ResearchKit开源地址
* [苹果开源框架ResearchKit简介](http://www.cocoachina.com/ios/20160426/16019.html) - ResearchKit 是一个由 Apple 推出的开源框架，它可以让研究人员和开发人员创建用于医疗研究的强大应用。您可以轻松地使用各种各样的可定制模块，您还可以在这些模块的基础上创建可视化授权工作流、实时的动态活动任务，以及调查报告，然后将它们与社区一同分享。由于 ResearchKit 能够与 HealthKit 无缝衔接，因此研究人员可以在他们的研究中获取更多有关的数据——例如日常步数、消耗的卡路里，以及心率等信息。

# 动画

## 开源的动画框架
* [MBMotion](https://github.com/mmoaay/MBMotion) - 随便实现的特效，正在不断丰富中，相关文章介绍[非常棒的特效-MBMotion](http://www.superqq.com/blog/2015/12/11/mbmotion-great-effect/)
* [DCAnimationKit](https://github.com/daltoniam/DCAnimationKit) - A collection of animations for iOS Simply, just add water! DCAnimationKit is a category on UIView to make animations easy to perform.

### pop

* [聊聊动画引擎 pop](http://ios.jobbole.com/84717/)

## 介绍动画的博文

* [iOS 7 UIKit Dynamic 学习总结](http://vit0.com/blog/2014/03/08/ios-7-uikit-dynamic-xue-xi-zong-jie/) - iOS 7 中推出的UIKit Dynamics，主要带来了模拟现实的二维动画效果，Apple 的高度封装让开发者不用知道太多物理知识也可以开发出逼真的物理动画。

# 并发-多线程

# GCD
* [GCD 使用指南](http://swift.gg/2016/05/05/the-gcd-handbook/) - 相应地英文原文：[http://khanlou.com/2016/04/the-GCD-handbook/](http://khanlou.com/2016/04/the-GCD-handbook/)

# Runtime

* [Objective-C Runtime 运行时之一：类与对象](http://southpeak.github.io/blog/2014/10/25/objective-c-runtime-yun-xing-shi-zhi-lei-yu-dui-xiang/) - 南峰子介绍Runtime系列
* [黑魔法——“低版本中使用高版本中出现的类”之技术实现原理详解](http://www.jianshu.com/p/55180ade32d1)
* [iOS中利用 runtime 一键改变字体](http://www.jianshu.com/p/b9fdd17c525e)
* [从源代码看 ObjC 中消息的发送](http://draveness.me/message/)
* [Objective-C Runtime 1小时入门教程](https://www.ianisme.com/ios/2019.html)

# Category

收集的一些有用的分类

## UIImage

* [iOS中使用blend改变图片颜色](https://onevcat.com/2013/04/using-blending-in-ios/) - 相应的[Demo](https://github.com/onevcat/VVImageTint)

# 性能优化

* [微信读书 iOS 性能优化总结](http://gold.xitu.io/entry/572866f62e958a00657cc19e) - 微信读书作为一款阅读类的新产品，目前还处于快速迭代，不断尝试的过程中，性能问题也在业务的不断累积中逐渐体现出来。最近的 1.3.0 版本发布后，关于性能问题的用户反馈逐渐增多，为此，团队开始做一些针对性的性能问题优化。本文将从发现问题、解决问题和预防问题三个方面进行总结。
* [离屏渲染优化](http://www.jianshu.com/p/ca51c9d3575b)

# 设计模式

* [iOS 中的设计模式 (Swift版本) Part 1 ](http://blog.callmewhy.com/2014/12/29/introducing-ios-design-patterns-in-swift-part-1/) - 原文英文版本请点击:[ Introducing iOS Design Patterns in Swift – Part 1/2 ](https://www.raywenderlich.com/86477/introducing-ios-design-patterns-in-swift-part-1)
* [OODesign](http://www.oodesign.com/) - 一个介绍各个设计模式的网站

## 类簇

* [从NSArray看类簇](http://blog.sunnyxx.com/2014/12/18/class-cluster/)
* [类簇在iOS开发中的应用](http://limboy.me/ios/2014/01/04/class-cluster.html)
* [一个iOS菜菜的白话文记录 - Class Cluster 类簇](http://xiongzenghuidegithub.github.io/blog/2016/05/09/class-cluster-lei-cu/)

## MVVM

* [Introduction to Protocol-Oriented MVVM](https://realm.io/news/doios-natasha-murashev-protocol-oriented-mvvm/)

# 架构设计

* [iOS移动端架构的那些事](http://www.jianshu.com/p/15e5b83ab70e)

# 网络编程

* [数字签名是什么？](http://www.ruanyifeng.com/blog/2011/08/what_is_a_digital_signature.html?20110811101638) - 它用图片通俗易懂地解释了，"数字签名"（digital signature）和"数字证书"（digital certificate）到底是什么。
* [HTTP in iOS你看我就够](http://www.jianshu.com/p/42d9cc1dde10)
* [iOS开发网络篇之文件下载、大文件下载、断点下载](http://www.jianshu.com/p/f65e32012f07?utm_source=tuicool)

# 重构

* [高速公路换轮胎——为遗留系统替换数据库](http://www.jianshu.com/p/d684693f1d77)

# 持续集成

* [构建iOS持续集成平台（一）——自动化构建和依赖管理](http://www.infoq.com/cn/articles/build-ios-continuous-integration-platform-part1)
* [构建iOS持续集成平台（二）——测试框架](http://www.infoq.com/cn/articles/build-ios-continuous-integration-platform-part2)
* [构建iOS持续集成平台（三）——CI服务器与自动化部署](http://www.infoq.com/cn/articles/build-ios-continuous-integration-platform-part3)
* [Jenkins+GitHub+Xcode+fir搭了一个持续集成环境](http://www.jianshu.com/p/a17167274463#)
* [豆瓣移动App持续集成和测试实践](http://wenku.it168.com/d_001515405.shtml)
* [在已有项目上构建持续集成平台](http://www.jianshu.com/p/39e4c8654d44#ios)
* [fir.im weekly - 「 持续集成 」实践教程合集](http://blog.fir.im/fir_im_weekly160505/)

# Git教程

* [Pro Git 第二版](https://git-scm.com/book/zh/v2) - 学习Git不错的入门教程
* [Pro Git 第一版](http://git.oschina.net/progit/)
* [廖雪峰的官方网站 - Git教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

# 书籍

* [禅与 Objective-C 编程艺术 （Zen and the Art of the Objective-C Craftsmanship 中文翻译）](https://github.com/oa414/objc-zen-book-cn)

# 工具

## Xcode插件

* [Xcode升级插件失效的解决办法以及使用](http://www.jianshu.com/p/df44a2e7ee9a)

* [Injection Plugin for Xcode](https://github.com/johnno1962/injectionforxcode) - Injection Plugin For Xcode 是 Xcode 上的一个插件。利用它可以修改应用代码，实时在模拟器或实机上看到效果而不需要重启应用。
* [一只快速生成代码的Xcode插件FastStub](http://mrpeak.cn/blog/faststub/) - 插件地址：[Github](https://github.com/music4kid/FastStub-Xcode)

## Cocoapods

* [理解Cocoapods](https://segmentfault.com/a/1190000005041357) - 对于做 iOS 开发的朋友来说，Cocoapods 是一件不必可少的得利工具，它是一个管理第三方库，并且解决其依赖关系的工具，但是有很多朋友对其运作的机制知其然却不知其所以然
* [Cocoapods完整教程](http://www.henishuo.com/cocoapods-use/)

Cocoapods系列教程
* [CocoaPods的简介及安装和使用 ](http://blog.csdn.net/eduora_meimei/article/details/44410373)
* [使用Cocoapods创建私有podspec](http://blog.wtlucky.com/blog/2015/02/26/create-private-podspec/)
* [如何写一个Pod，并发布到CocoaPods上 ](http://blog.csdn.net/becomedragonlong/article/details/45933345#0-tsina-1-22915-397232)
* [CocoaPods的一些略为高级一丁点的使用](http://www.cocoachina.com/ios/20150916/13384.html)
* [在Swift中使用CocoaPods](http://andelf.github.io/blog/2014/06/23/use-cocoapods-with-swift/)
* [Creating Your First CocoaPod](http://code.tutsplus.com/tutorials/creating-your-first-cocoapod--cms-24332)

另外一个系列的教程
* [Cocoapods系列教程(一)——入门](http://www.pluto-y.com/cocoapods-getting-stared/)
* [Cocoapods系列教程(二)——开源主义接班人 ](http://www.pluto-y.com/cocoapods-contribute-for-open-source/)
* [Cocoapods系列教程(三)——私有库管理和模块化管理 ](http://blog.csdn.net/youtk21ai/article/details/50762936)

## Hexo个人博客

* [hexo常用命令笔记](https://segmentfault.com/a/1190000002632530)

* [如何搭建一个独立博客——简明Github Pages与Hexo教程](http://www.jianshu.com/p/05289a4bc8b2) - 摘要：这是一篇很详尽的独立博客搭建教程，里面介绍了域名注册、DNS设置、github和Hexo设置等过程，这是我写得最长的一篇教程。我想将我搭建独立博客的过程在一篇文章中尽可能详细地写出来，希望能给后来者一个明确的指引，同时用这篇教程开篇，正式开始我的第八大洲之旅。
* [Mac下搭建Hexo博客教程](http://yebujimo.com/2015/03/15/Mac%E4%B8%8B%E6%90%AD%E5%BB%BAHexo%E5%8D%9A%E5%AE%A2%E6%95%99%E7%A8%8B/)
* [将Github提供的二级域名与自己的域名绑定](http://wangcaiyong.com/2015/06/25/custom-your-domain/)

### Hexo 主题

* [NexT](https://github.com/iissnan/hexo-theme-next) - 目前使用人数做多的一个博客主题
* [https://github.com/MOxFIVE/hexo-theme-yelee](https://github.com/MOxFIVE/hexo-theme-yelee)

## Markdown
### 在线编辑器
* [Cmd Markdown在线编辑器](https://www.zybuluo.com/mdeditor) - 国内的一款markdown在线编辑器，非常的好用，推荐。
* [dillinger](http://dillinger.io/) - 漂亮强大，支持md, html, pdf 文件导出。支持dropbox, onedrive，google drive, github. 来自国外，可能不够稳定。 

### 语法
* [markdown简明语法](http://ibruce.info/2013/11/26/markdown/)
* [Markdown 语法说明 (简体中文版)](http://wowubuntu.com/markdown/)
