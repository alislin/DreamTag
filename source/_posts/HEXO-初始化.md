---
title: Hexo 初始化
date: 2019-02-19 15:40:45
tags: Hexo
---
对比了若干静态生成网站的工具，Jekyll、Octopress、Hexo 等 。最后选择了Hexo作为基础工具。选择理由如下：
1. nodejs安装
2. markdown支持
3. 鉴于简单和复杂之间，可以单纯使用markdown作为文档编写。但也可以使用插件折腾。中文帮助也比较完善。
 
使用非常简单，总共用以下几条指令：  
安装Hexo
```
$npm install -g hexo-cli
```
创建网站
```
$hexo init 网站名称
```
创建文章
```
$hexo new "文章标题"
```
生成
```
$hexo g
```
网站查看
```
$hexo s
```
当然配置和插件就接下来后续折腾了。
