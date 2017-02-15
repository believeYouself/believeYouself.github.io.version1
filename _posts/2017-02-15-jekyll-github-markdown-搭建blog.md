---
layout: post
title: jekyll+github pages+markdown=blog
---

## 基本概念 ##       

github pages  
> GitHub 为每一个用户分配了一个二级域名<user-id>.github.io，用户为自己的二级域名创建主页很容易，只要在托管空间下创建一个名为<user-id>.github.io的版本库，向其master分支提交网站静态页面即可，其中网站首页为index.html。还可以为每个项目设置主页，项目主页也通过此二级域名进行访问，例如gotgithub用户创建的helloworld项目如果启用了项目主页，则可通过网址http://gotgithub.github.io/helloworld/访问。   

jekyll
> Jekyll是一种简单的、适用于博客的、静态网站生成引擎。它使用一个模板目录作为网站布局的基础框架，支持Markdown、Textile等标记语言的解析，提供了模板、变量、插件等功能，最终生成一个完整的静态Web站点。说白了就是，只要安装Jekyll的规范和结构，不用写html，就可以生成网站。
> Jekyll是用Ruby编写的，
> 安装Jekyll最简单的方法是通过RubyGems(gem)安装，会自动将Jekyll依赖的directory_watcher、liquid、open4、maruku和classifier等Gem包一并安装。$ gem install jekyll
	
jekyll与github pages的关系
> jekyll是github pages后台运行的解析引擎。

markdown
> 和html、textile一样，是一种文本标记语言，可快速掌握其语法，写优美的博客。 

git基本用法
>暂存所有内容： git add .
提交暂存内容到本地git库：$ git commit -m "first post"  
$ git remote add origin https://github.com/username/jekyll_demo.git     
将本地git库内容提交到远程git库中gh-pages分支：$ git push origin gh-pages       
克隆远程项目： git clone http://XXX.XXX/sq-group/XXX.git        
  
## 搭建的基本步骤 ##
> 1. 本地搭建jekyll环境。      
> 2. 自己创建或克隆他人的jekyll博客到本地，修改完善。          
> 3. 将本地jekyll博客用git提交到github pages上部署。       
> 4. 日常如何写博客：本地写markdown格式博客，用git提交到github发不。

