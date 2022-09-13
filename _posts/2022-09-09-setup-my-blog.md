---
title: 个人博客搭建
tags: 博客搭建
---

# 参考资料
[1] https://pages.github.com/                        使用github提供的写博客的方法

[2] https://github.com/kitian616/jekyll-TeXt-theme   本博客使用的主题

[3] https://www.jekyll.com.cn/docs/                  本地调试时安装的依赖 

[4] https://zhuanlan.zhihu.com/p/143586985           Markdown语法大全


# 基于jekyll-TeXt-theme搭建

先在自己的github创建一个空仓库，如https://github.com/forsakening/forsakening.github.io

将 https://github.com/kitian616/jekyll-TeXt-theme 仓库的代码push至上述自己的仓库中

访问forsakening.github.io即可

# 本地windows测试环境
## 安装ruby、git等工具包
https://www.ruby-lang.org/en/downloads/ 在此网站上安装ruby，版本实测选择2.6左右的版本较好

## 安装bundle
gem install jekyll bundler
bundle install --path vendor/bundle
参考 https://www.jekyll.com.cn/docs/

## 测试
bundle exec jekyll clean
bundle exec jekyll serve

本地浏览器执行127.0.0.1:4000



