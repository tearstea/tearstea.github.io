---
layout: post
title: Webpack打包vue CLI 3.0项目之后生成的dist文件该怎么启动运行
subtitle: vue项目打包，如何部署在express服务器上运行
date: 2018-09-22
author: HL
header-img: img/postbg-10-20.jpg
catalog: false
tags:
      - vue项目打包
      - express
---

# 前言

作为前端，经常使用 vue 框架做页面，项目完成后经常要打包上线，为了减少上线麻烦，需要先行测试。几经百度，总算测试了个有效的方式。亲测，有效，如果无效，可能自己项目中的图片引用文件路径路径等可能出现问题。不断在 BUG 中前行，方能有所成果。举例如下，所进行的是一个 vue CLI 3.0 的项目。我的 vue 项目结构如下：

<img src="/PigThird/Third1.jpg" width="500">

## 第一步

进入 vue 项目，打包，打开 gitbash，找到该项目文件， 然后输入 npm run build，进行打包。生成 dist 文件，即为打包后的文件。

<img src="/PigThird/Third2.jpg" width="500">

## 第二步

在 dist 文件中，用浏览器打开 index.html,发现是空白页。我的为什么不是空白页，是因为本身在 index.html 文件中有加载 loading 动画。所以会出现如下画面，但加载不了页面内容

<img src="/PigThird/Third3.jpg" width="500">

## 第三步

安装 express-generator 生成器。在电脑里，新建一个文件夹，我建的是 RuningDist 文件，打开 gitbash，找到该项目文件，执行 $ npm install express-generator -g 进行安装。如果太慢，可用 cnpm 安装。

<img src="/PigThird/Third4.jpg" width="500">

## 第四步

创建一个 express 项目，执行 $ express expressTest （expressTest 是项目名，自己可以自己命名。也将是即将运行 dist 文件的根文件）

<img src="/PigThird/Third5.jpg" width="500">

## 第五步

进入 expressTest 目录，执行 $ cd expressTest

<img src="/PigThird/Third6.jpg" width="500">

## 第六步

复制 vue 项目中 dist 文件下所有的内容到 expressTest 文件夹下的 public 文件夹中。如图

<img src="/PigThird/Third7.jpg" width="500">

## 第七步

安装项目依赖，执行　 $ npm install

<img src="/PigThird/Third8.png" width="500">

## 第八步

１.运行 $ npm start 启动 expressTest

<img src="/PigThird/Third9.jpg" width="500">

２.当看到如下图示即可在浏览器中输入http://localhost:3000 , 就可以看到效果了。之前看着一直 gitbash 中一直没啥反应，还以为出了什么问题呢。

<img src="/PigThird/Third10.jpg" width="500">

３.在浏览器中可以看到如下。

<img src="/PigThird/Third11.jpg" width="500">

４.gitbash 中，将是这样的。

<img src="/PigThird/Third12.jpg" width="500">

至此，整个项目打包是成功的。如果仍然是空白情况，那么久要检查原始项目的路径问题了。
