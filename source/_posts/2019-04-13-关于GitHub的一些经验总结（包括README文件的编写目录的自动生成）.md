---
layout: post
title: 解决两个 Android 模拟器之间无法网络通信的问题
categories: Android
description: 如何配置，让同一台 PC 上的两个 Android 模拟器之间能够使用 TCP 通信？
keywords: Android, Emulator, TCP
tags:
	- Git
	- GitHub
---

本系列文章在 <https://github.com/freestylefly/javaStudy> 持(huan)续(ying)更(jia)新(ru)中，欢迎有兴趣的童鞋们关注。

## 一、README.md上传图片
需要注意的是一定要图片先上传到图床，我这边用的有两个
1、[图床](https://imgchr.com/)
2、[七牛云](https://www.qiniu.com/)
关于七牛云我会出另外一篇文章细说
注意：不管是截图的图片还是本地上传的图片都要上传到图床上，，然后复制URL才可以在GitHub中显示

## 二、README.md自动生成目录
不能用Markdown的【TCG】自动生成目录，在GitHub上是不显示的
我的办法是：
1、[点开网站](https://sleepeatcode.com/ghtoc)
2、将GitHub的README.md的URL复制，自动生成目录，但是这是不全的
3、复制目录到README.md文件，需要在后面的括号处加上#文件名，这个是我能找到的比较简单的办法了，比手动敲简单
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190331070938177.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQzMjcwMDc0,size_16,color_FFFFFF,t_70)
特别注意：#后面不要加任何特殊字符和数字，目录不要编号，否则不成功，内部跳转不成功的很大部分原因也是因为内部编号了。

## >三、我的GitHub
https://github.com/freestylefly/javaStudy#ajax
期待你的加入！，有什么不懂的可以在GitHub上留言问我。

------
# 本文章已同步至我的GitHub仓库：<a href="https://github.com/freestylefly/javaStudy">Javastudy</a>,期待您的加入:blush:
<img src="http://pp8g2fyug.bkt.clouddn.com/github.jpg" width=""/>

# 本文章已同步至<a href="https://freestylefly.github.io/">苍何的个人博客</a>,可以直接在博客上留言哦:blush:
<img src="http://pp8g2fyug.bkt.clouddn.com/myblog..png" width=""/>

# 来我的微信公众号玩耍呗:blush:
<img src="http://pp8g2fyug.bkt.clouddn.com/weixingongzhonghao.jpg" width=""/>

# 扫码无套路关注我的<a href="https://blog.csdn.net/qq_43270074?orderby=UpdateTime">CSDN</a>博客:blush:
<img src="http://pp8g2fyug.bkt.clouddn.com/CSDN.png" width=""/>