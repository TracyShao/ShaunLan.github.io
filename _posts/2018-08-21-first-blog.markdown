---
layout:     post
title:      "First Blog"
subtitle:   "Hello somebody"
date:       2018-08-21
author:     "lantian"
header-img: "img/post-bg-2015.jpg"
tags:
    - 技术
---

## 前言
- 一直想要搞一个blog，但是自己单独搞一个域名然后搭一个服务器又太费劲，于是就想着用GitHub pages 弄一个博客，要是能够坚持下去创作自己就以后搭一个

## 如何搭建GitHub pages blog 
- 本blog基于GitHub pages 搭建，模板fork的huxpro (https://github.com/Huxpro/huxblog-boilerplate)
- 无编程基础的，快速使用GitHub pages 搭建博客可以参考：(https://www.jianshu.com/p/e68fba58f75c)
- 有编程基础的，最简单搭建一个GitHub pages
  - 新建一个repository
  - 点击Setting往下拖找到GitHub pages 然后先随便选择choose theme之后commit提交成功，再次进入setting中此时GitHub pages 就会出现 “Your site is ready to be published at XXX ” 点击XXX就会进入GitHub pages 了
  - 之后你就可以按照GitHub pages的规定来更改你的repository就行了（有前端编程基础的）
  - 为了避免造轮子可以fork现成的模板，我就是fork别人的模板进行搭建的
  - 模板fork到本地后，要想在本地显示跟GitHub pages 一样的效果需要，安装jekyll,这个东西依赖于ruby，所以本地如果没有安装ruby的需要自行Google安装，还要安装包管理器 gem等等。之后还有几个小坑自行解决就好
  - 安装完jekyll后只要在项目根目录下 jekyll serve 然后就会出现  Server address: http://127.0.0.1:4000/ 这样的信息，浏览器直接访问 Server address的地址即可
  - 剩下的就是不断地完善和修改自己的blog喽