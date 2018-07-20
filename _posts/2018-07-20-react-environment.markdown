---
layout:    post
title:     "react环境搭建!"
subtitle:   " \"如何搭建react环境\""
date:       2018/07/20
author:     "xueyingying"
header-img: "img/in-post/first-page/first-bg.png"
catalog: true
tags:
  - react

---

> "搭建react环境"

## 前言

总结一键搭建react环境：

    1.create-react-app搭建

    2.ykit搭建

    3.antd搭建

    4.dva搭建

---

## 正文

#### create-react-app

1.安装create-react-app脚手架：npm  install -g  create-react-app

2.一键搭建react环境：create-react-app 你要创建的项目名

3.cd进入项目运行：npm run start 自动跳转到浏览器网页

---

#### ykit

1.安装ykit： npm install ykit -g

2.创建项目：mkdir 项目名

3.cd进入项目搭建环境：ykit init react

4.运行： ykit server

---

#### antd

1.安装antd脚手架： npm install antd-init -g

2.创建项目：mkdir 项目名

3.cd进入项目搭建环境：antd-init

4.运行： npm start

5.在浏览器中访问localhost:8000；不会自动跳转

---

#### dva

1.安装dva脚手架：npm  install dva-cli -g

2.一键搭建react环境：dva new 你要创建的项目名

3.cd进入项目运行：npm run start 自动跳转到浏览器网页

---

#### 问题

1.npm安装脚手架时报错，可以用yarn安装：yarn global add 所要安装的名称

2.运行时报错，可能是不在创建的项目文件夹下

---
