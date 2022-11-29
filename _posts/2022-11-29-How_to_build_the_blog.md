---
title: "怎么快速搭建博客呢？"
date: 2022-11-29
layout: post
tag-name: 技术
toc: true
---
# 准备工作
本文的介绍是使用Github Pages来托管，Jekyll开搭建，这样我们可以轻而易举地发布我们的博客。

所以，第一步：你需要有github账号，如果没有的话，需要去[github官网](https://github.com/)注册一个。

第二步：创建仓库，输入名字，记得将仓库选为Public。

这两步也可以在[Github Pages](https://github.com/skills/github-pages)看到介绍。

# 安装Jekyll
## 先决条件

## 准备安装
打开[Jekyll官网](http://jekyllcn.com/)，安装步骤安装即可。
```bash
gem install bundler jekyll
```
可通过创建一个jekyll site，测试安装是否成功。
```bash
jekyll new myblog
```
执行完成后，`cd`到新创建的目录并启动server：
```bash
cd myblog
bundle exec jekyll serve
```
也可以通过`jekyll s`来启动。
# 选择主题
我们在[Jekyll主题官网](http://jekyllthemes.org/)选择主题。
bundle install
# Jekyll语法介绍
