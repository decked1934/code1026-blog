---
title: 用hexo和git搭建个人博客
date: 2018-10-25 10:52:34
tags:
---
# 用hexo+github 搭建个人博客  
[样板参考](http://htmler.cn) 
## 一·环境搭建
1·node
 why? hexo是一款基于node开发出来的博客框架
 what?node:基于JavaScript语法的一款WEB服务器
 how?  [官网地址](https://nodejs.org/zh-cn/ )选择V8.X版本
2·git (版本控制器) 分布式  
what 版本控制器
github 全球最大的开源代码托管平台
why 通过github托管博客项目
how [官网](https://git-scm.com/) 下载安装包

## 二.项目环境搭建
1·安装hexo脚手架：通过npm包管理器
npm:基于Node的包管理器(类似于APP store)
原生 ==》 插件==》 框架
```bash
npm install hexo-cli -g #安装hexo依赖包
install #导入 安装
hexo-cli:hexo #脚手架  
clear ctrl+L #清屏
-g #全局安装 global  （对应局部）
```

2·npm切换淘宝镜像 解决npm国内慢的问题


## 三.初始化一个博客项目
1.在桌面右键“git bash here”
2.初始化项目

```bash
hexo init blog #初始化文件夹
```
3.切换blog文件夹

```bash
cd blog    #change dirte
ls #显示当前路径文件   
ls -a #显示当前路径所有文件
pwd #显示当前全路径    
```

4.安装项目依赖包
```bash
npm install #安装命令
```
5.启动hexo服务

```bash
hexo s           #启动服务server 
ctrl+c  # 关闭服务
```

http://localhost:4000   关闭是 

## 四.Linux常用命令

```bash
cd  #目录名   路径切换
pwd         #查看当前路径
ls -a       #查看当前路径所有文件及目录
cd ..      #回到上级目录
```

下载 VSCODE 安装
选择打开文件夹bolg 
source 源文件 _posts 页面文章内容
nod_modules 全部安装包
.gitignore  不需要上传的文件
{}package.json   

```bash
ctrl+~ #呼出服务器控制
```