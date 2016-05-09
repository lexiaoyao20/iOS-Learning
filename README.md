# iOS Learning

iOS学习资源整理，包含一些开源组件和博客文章。

### 目录

- [控件](#控件)
  - [UIButton](#uibutton) 
  - [Chart-图表控件](#chart-图表控件)
    - [K线图](#k线图)
- [框架](#框架)
  - [AVFoundation](#avfoundation)
  - [Quick Look Framework](#quick-look-framework)
  - [Quartz 2D](#quartz-2d)
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
- [架构设计](#架构设计)
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

# 控件

## UIButton
* [LCUIKit](https://github.com/lianchengjiang/LCUIKit) - 可以设置`UIButton`的*Text*和*Image*的相对位置，如上下左右等。
* [UIButton 的 imageEdgeInsets 和 titleEdgeInsets](http://www.jianshu.com/p/62850b201049)

## Chart-图表控件

### K线图

* [YKLineChartView](https://github.com/chenyk0317/YKLineChartView) - iOS 股票的K线图 分时图。
* [Cocoa-Charts](https://github.com/limccn/Cocoa-Charts) - Open-source iPhone/iPad graph/chart framework includes line chart,stick chart,candlestick chart,pie chart,spider-web chart etc. Based on iOS graph SDK, Using native Objective-c Codes.
* [BBStockChartView](https://github.com/chenxiaoyu3/BBStockChartView) - An iOS stock chart view, K-Line, volume Line.
* [KlineInSwift](https://github.com/mengmanzbh/KlineInSwift) - 用swift写的K线图

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


# 动画

## 开源的动画框架
* [MBMotion](https://github.com/mmoaay/MBMotion) - 随便实现的特效，正在不断丰富中，相关文章介绍[非常棒的特效-MBMotion](http://www.superqq.com/blog/2015/12/11/mbmotion-great-effect/)

### pop

* [聊聊动画引擎 pop](http://ios.jobbole.com/84717/)

## 介绍动画的博文

TODO: 

# 并发-多线程

# GCD
* [GCD 使用指南](http://swift.gg/2016/05/05/the-gcd-handbook/) - 相应地英文原文：[http://khanlou.com/2016/04/the-GCD-handbook/](http://khanlou.com/2016/04/the-GCD-handbook/)

# Runtime

* [Objective-C Runtime 运行时之一：类与对象](http://southpeak.github.io/blog/2014/10/25/objective-c-runtime-yun-xing-shi-zhi-lei-yu-dui-xiang/) - 南峰子介绍Runtime系列
* [黑魔法——“低版本中使用高版本中出现的类”之技术实现原理详解](http://www.jianshu.com/p/55180ade32d1)
* [iOS中利用 runtime 一键改变字体](http://www.jianshu.com/p/b9fdd17c525e)

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

# 架构设计

* [iOS移动端架构的那些事](http://www.jianshu.com/p/15e5b83ab70e)

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

## Cocoapods

* [理解Cocoapods](https://segmentfault.com/a/1190000005041357) - 对于做 iOS 开发的朋友来说，Cocoapods 是一件不必可少的得利工具，它是一个管理第三方库，并且解决其依赖关系的工具，但是有很多朋友对其运作的机制知其然却不知其所以然

## Hexo个人博客

* [hexo常用命令笔记](https://segmentfault.com/a/1190000002632530)

* [如何搭建一个独立博客——简明Github Pages与Hexo教程](http://www.jianshu.com/p/05289a4bc8b2) - 摘要：这是一篇很详尽的独立博客搭建教程，里面介绍了域名注册、DNS设置、github和Hexo设置等过程，这是我写得最长的一篇教程。我想将我搭建独立博客的过程在一篇文章中尽可能详细地写出来，希望能给后来者一个明确的指引，同时用这篇教程开篇，正式开始我的第八大洲之旅。
* [Mac下搭建Hexo博客教程](http://yebujimo.com/2015/03/15/Mac%E4%B8%8B%E6%90%AD%E5%BB%BAHexo%E5%8D%9A%E5%AE%A2%E6%95%99%E7%A8%8B/)
* [将Github提供的二级域名与自己的域名绑定](http://wangcaiyong.com/2015/06/25/custom-your-domain/)

### Hexo 主题

* [https://github.com/MOxFIVE/hexo-theme-yelee](https://github.com/MOxFIVE/hexo-theme-yelee)

## Markdown
### 在线编辑器
* [Cmd Markdown在线编辑器](https://www.zybuluo.com/mdeditor) - 国内的一款markdown在线编辑器，非常的好用，推荐。
* [dillinger](http://dillinger.io/) - 漂亮强大，支持md, html, pdf 文件导出。支持dropbox, onedrive，google drive, github. 来自国外，可能不够稳定。 

### 语法
* [markdown简明语法](http://ibruce.info/2013/11/26/markdown/)
* [Markdown 语法说明 (简体中文版)](http://wowubuntu.com/markdown/)
