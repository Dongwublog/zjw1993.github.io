---
layout: post
title:  "如何在jekyll上编辑blog"
date:   2016-8-9
categories: markdown
tags: jekyll markdown
---

* content
{:toc}
　　现在的社会很多人都写自己的blog，blog是一个书写自己一些想法并保存、记录、分享的工具。所以说，现今社会拥有一个自己的blog网站是十分必要的




### 背景
　　利用github搭建blog，选好合适jekyll模板，准备书写blog

### 编写地点
　　1.本地编写

1.进入github官网，登录github账号，进入repositories（仓库）Dongwublog.github.io，将项目内容clone到本地

2.在本地命令行中进入/dongwublog.github.io/_posts文件使用编辑器（如vi、retext等）编写blog

　　2.github网页直接编写

1.进入github官网，登录github账号，进入repositories（仓库）Dongwublog.github.io。

2.进入_posts文件create new file直接编辑

### 博客文件创建
　　博客以“年-月-日-标题.md”形式创建在_posts文件内。

### 编写blog格式

1.本地编辑模式（以Ubuntu为例）
![markdown](/images/posts/markdown/1.png)

2.github网页编辑模式
![markdown](/images/posts/markdown/2.png)

**tip**：图片中红框中空格均为全角空格。blog演示部分与隐藏部分使用4个空行隔开

### markdown语法介绍
　　Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。

　　1.markdown语法规则官方介绍[http://daringfireball.net/projects/markdown/syntax](http://daringfireball.net/projects/markdown/syntax)

　　2.markdown语法规则中文介绍[http://www.appinn.com/markdown/](http://www.appinn.com/markdown/)

### blog文件保存上传提交
　　1.本地上传blog文件

1.git add year-month-day-title.md

2.git commit -m"文件注释"

3.git push

　　2.github网页直接上传

编辑blog完成后，commit new file
　　
