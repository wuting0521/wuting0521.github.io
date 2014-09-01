---
layout: post
title: "用Jeykll和Github Pages来搭建博客"
description: ""
category: "blog"
tags: Github Jekyll
---
{% include JB/setup %}

###起源
搭建这个博客也算是纯属机缘巧合，原因是最近在搜索一些技术文档时发现以github.io作为根域名的技术特别多，于是害死猫的好奇心就这么被勾起来了。然后发现依靠github搭建博客的成本大大降低，于是就尝试性地这么搭了一个个人博客玩玩。

###Github.io
既然根域名是github.io，那么就遵照着github.io给予地步骤一步步做，其实就可以完整地搭建一个博客。步骤上，无非就是先创建一个username.github.io的代码仓库，将博客的整个代码推送到远程仓库，剩下的编译、打包、发布全部由Github来完成，大大地降低了搭建一个博客的技术成本。至少对于我这个技术渣来说，这个博客还是搭建起来并且可以使用的了。 ＝）

###Jekyll
Jekyll是一个简单地博客静态网站模版，使用起来还是比较简单地。当然我也是刚刚上手，还有许多东西需要看一看。Jekyll是依靠规范地目录结构来维护网站的，譬如这篇文章就保存在_post文件夹下。
使用Jekyll Bootstrap可以快速地生成一套标准化地Jekyll目录结构。Jekyll Bootstrap支持命令行命令操作，对我这个使用命令行地半吊子来说，还是很方便的。

###Markdown
Jekyll和Github IO支持Markdown脚本，其实我个人也不知道Markdown是什么，就现在的理解，Markdown应该就是支持标签的一个轻量级的语言，目前这篇文章就在用Markdown的一部分标签撰写，还是挺方便的。当然Markdown应该还有更多强大的功能等待发掘。

###编辑器
不知道Mac有没有其他的强大的文本编辑器，目前使用的TextWrangler，感觉已经很强大了，待找到觉得更好用的，我再贴过来。

