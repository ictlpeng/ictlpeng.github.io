---
layout: post
title: 使用reviewBoard来做代码review
---


## 安装

1.	安装python2.7由于centos6.8默认是python2.6，而reviewboard需要python2.7，否则会报语法错误。1)	下载python2.7.3的源码包2)	安装python，注意需要提前安装sqllite，curl和openssl环境，这样python就会自动编译出模块3)	注意编译选项为—enable-shared2.	安装apache：yum –y install httpd
3.	按照官网文档进行安装和设置https://www.reviewboard.org/docs/manual/2.5/admin/installation/linux/https://www.reviewboard.org/docs/manual/2.5/admin/installation/creating-sites/#creating-sites


## 问题


### Permission denied: access to /修改文件和目录权限，注意.htaccess### python版本问题重新编译mod_wsgi




