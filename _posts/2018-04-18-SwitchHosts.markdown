---
layout:    post
title:     "SwitchHosts!"
subtitle:   " \"管理host的工具\""
date:       2018/04/18
author:     "xueyingying"
header-img: "img/in-post/first-page/first-bg.png"
catalog: true
tags:
  - 工具

---

> “使用SwitchHosts来管理host”


## 前言

在我们进行项目开发时，有时候需要改变host来使某一些资源指向我们想要指向的地方；

举个例子：现在有一个线上项目要修改一些需求，把线上项目拉下来之后，自己在本地一通修改，在自测时，你想让资源指向你的本地，因为线上并不存在你刚刚修改的内容；
那么此时，你想让那些资源指向自己的本地，就需要修改host来实现

有人说：我直接修改电脑上hosts的文件就可以了，当然可以这么做(如果你不闲麻烦的话)，因为你可能不止开发一个项目，要修改的host也不止一个

---

## 正文

> 正式介绍SwitchHosts

#### 介绍

使用起来其实很简单：

1.SwitchHosts的安装接不多介绍了，自行下载就好

2.打开后的界面

![Alt text](/img/in-post/switchhosts/hosts.png)

3.定义自己的host规则

左侧的列表栏，是添加的文件

---

#### 添加host方案

第一种：侧边栏最下面的“+”
![Alt text](/img/in-post/switchhosts/add-host1.png)

第二种：最上侧导航栏 “文件” -> "新建"

![Alt text](/img/in-post/switchhosts/add-host2.png) 

最后都会弹出以下内容：添加host方案名确定就成功了

![Alt text](/img/in-post/switchhosts/add-host3.png) 

---

#### 添加host规则

侧边栏的每一个host方案都对应右侧的内容；其内容就是你要添加的host规则

![Alt text](/img/in-post/switchhosts/hosts.png)

你想要应用哪一条host方案，勾选就可以了;当然可以同时应用多条

![Alt text](/img/in-post/switchhosts/add-host4.png) 

点击前面的类似于笔的标志，进入到以下界面，可以修改该或删除host方案

![Alt text](/img/in-post/switchhosts/delete-host.png) 

---






