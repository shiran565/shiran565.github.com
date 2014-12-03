---
layout: post
title: "使用jekyll搭建个人博客"
description: "jekyll，个人博客，github pages"
tagline: "Logic Operation In Python"
category: "经验总结"
tags: [jekyll,jekyll搭建,github pages]
---
{% include JB/setup %}

##背景知识
###*GitHub Pages*是什么？

github大家都知道，它向用户提供项目源码托管服务，许多知名的开源项目都进驻其中，各个项目免不了要想其他人作些介绍，于是github提供了GitPages功能，用户可以用它来自定义页面作为项目或者个人空间的首页

页面的生成是通过jekyll来实现的，jekyll的介绍见[这里](http://jekyllrb.com/)

*简单介绍一下jekyll*

jekyll是一个用ruby写的简单的免费的Blog生成工具，类似WordPress。但是和WordPress又有很大的不同，原因是jekyll只是一个生成静态网页的工具，不需要数据库支持。但是可以配合第三方服务,例如disqus。最关键的是jekyll可以免费部署在Github上，而且可以绑定自己的域名。

