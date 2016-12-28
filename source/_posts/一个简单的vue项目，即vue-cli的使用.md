---
title: 一个简单的vue项目，即vue-cli的使用
---
## 一：node环境的安装

首先当然是安装node环境了，找到node官网，下载最新的node环境

* 安装之后打开cmd，输入 node -v 查看node版本号，输入 npm -v 查看npm版本号
* 如果显示’node’不是内部或外部命令，也不是可运行的程序，这就尴尬了，点击我的电脑右键，打开属性，然后是高级系统设置，然后是环境变量，然后是PATH，双击，复制下面的npm命令路径
C:\Users\Administrator\AppData\Roaming\npm;
* 然后再次打开cmd，输入 node -v 查看node版本号，输入 npm -v 查看npm版本号

## 二：安装淘宝镜像

* npm install -g cnpm –registry=https://registry.npm.taobao.org

## 三：安装webpack

* npm install webpack -g

## 四：安装vue脚手架

* npm install vue-cli -g

## 五：在硬盘上找一个文件夹放工程用的，在终端中进入该目录

* cd 目录路径

## 六：根据模板创建项目

* vue init webpack-simple 工程名字<工程名字不能用中文>
* 会有一些初始化的设置，如下输入:
Target directory exists. Continue? (Y/n)直接回车默认(然后会下载 vue2.0模板，这里可能需要连代理)
Project name (vue-test)直接回车默认
Project description (A Vue.js project) 直接回车默认
Author 写你自己的名字

## 七：cd 命令进入创建的工程目录

* vue init webpack-simple 工程名字<工程名字不能用中文>

## 八：安装项目依赖

* npm install

## 九：安装 vue 路由模块vue-router和网络请求模块vue-resource

* npm install vue-router vue-resource –save

## 十：启动项目模块vue-resource

* npm run dev

## 十一：写在后面

* 给一个掘金的详细教程
[点击我](https://aotu.io/notes/2016/10/13/vue2/?o2src=juejin&o2layout=compat)
