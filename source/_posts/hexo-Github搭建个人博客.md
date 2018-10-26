---
title: hexo+Github搭建个人博客
date: 2018-10-25 10:51:07
tags:
---
# 基础环境搭建
## 1、node
 why？  因为hexo是一款基于node开发出来的博客框架
 what？基于JavaScript语法的一款web服务器
 how？打开官网 https://nodejs.org/zh-cn/ 下载8.x的版本，双击下一步下一步安装
 ## 2、git
 what？版本控制器
 GitHub？全球最大的开源代码托管平台
 why?通过GitHub托管博客项目
 how？打开官网 https://git-scm.com/ 下载Git安装包，双击下一步下一步安装
 # 项目环境搭建
 ## 1、安装hexo脚手架：通过npm包管理器
 npm install hexo-cli -g
 npm:基于node的包管理器（类似于Apple store）
 install：导入、安装
 hexo-cll：hexo脚手架
 -g:全局
 ## 2、npm切换淘宝镜像（解决npm国内慢）：npm install -g cnpm --registry=https://registry.npm.taobao.org
 # 初始化一个博客项目

 ```bash
 1、在桌面右键“Git bash here”
 2、初始化项目
   hexo init blog
 3、切换到blog文件夹
   cd blog
 4、安装项目依赖包
    npm install
 5、启动hexo服务
    hexo s
```
# Linux  常用命令
 pwd 显示当前路径 
	   ls/ls -a 显示当前路径下所有文件及目录  
	   cd 文件名  进入文件夹（路径切换）
           cd .. 返回上一级  
	   clear/ctrl+L清屏
           hexo s 启动项目服务器
	   cd / 回到顶级目录/根目录
	   mkdir 文件名  新建一个文件夹
	   rmdir 文件名  删除一个文件夹
博客内容的编辑，美化用vscode