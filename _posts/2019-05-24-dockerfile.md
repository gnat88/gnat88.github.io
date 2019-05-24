---
layout: post
title: dockerfile语法
date:   2019-05-24 20:05:00 +0800
categories: 技术
tag: docker
---

* content
{:toc}


## docker file
##


## dockerfile语法

### CMD
提供container启动后的执行命令
CMD["./gw", "--addr", "hots:port"]
必须将每个参数都分开，如果写成 "—addr host:port" 是错误的格式

### add
将context上下文中的文件或者目录添加到container中, 如果识别到gz等丫说文件，会自动解压缩


### Volume
加载一个卷到Docker中
格式：volume  host_dir container_dir
-v host_dir:container_dir
-v container_dir 使用这种方式的时候，系统会在默认的目录新建一个目录映射到container中


