---
layout: post
title: "【分享】使用Jekyll搭建自己的Github博客"
categories: 基本能力
tags: blog
author: zukking
---

* content
{:toc}


2014年，我要感谢大一下学期的网页制作课程让我对做网页产生了浓厚的兴趣，并且在接下来的暑假中有能力跟辉哥一起做了学创传媒。这件事对我后来有很大启蒙，虽然项目因为种种不幸而夭折，但也算是探索校园新媒体的先行者。

后来我就发现自己经常会因为看到了太多新鲜的知识却不能及时消化而顾此失彼，经常忘记一些学过的东西。记录学习生活成了我的刚需。于是我开始做微信公众号，因为我实在找不出比这更好的办法。也感谢这些年来一直鼓励支持我的朋友们，你们是我坚持作自己的动力。今天在这里记一下使用Jekyll搭建自己的Github博客的过程，重拾那份初见般的美好。

[Github](http://github.com) ，一个听说过没见过的东西，咱也不知道是个啥，咱也不敢问。Github可以理解为就是一个代码仓库，我们可以创建自己的仓库，也可以复制[*fork*]别人的仓库经过修改供自己使用。Github给每一个用户都提供了一个个人页面[*githubpage*]的功能，只要根据规则创建就可以访问。

那么到底怎么做呢？其实我们只需要三样东西：GitHub账户；用账户名.github.io命名的仓库；仓库下的index.html文件。怎么样，是不是有种豁然开朗的感觉呢，没错。只要把本地的一个静态web站点整个的上传到我们新建的这个仓库就可以了。比如我本地的站点结构是这样子

![](https://raw.githubusercontent.com/mengshengjie/mengshengjie.github.io/master/_posts/Pic/jekyllblog_1.png)





用户名.github.io 的仓库



fork一个过来



下载到本机



通过Atom修改上传



通过Typora编辑Md文件
