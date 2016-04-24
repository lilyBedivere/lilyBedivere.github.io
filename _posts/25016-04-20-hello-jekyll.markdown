---
layout:     post
title:      "Welcome to Hzb' blog"
subtitle:   " \"Hello World,hello jekyll\""
date:       2016-04-20 9::50
author:     "Hzb"
header-img: "img/saber-bg.jpg"
tags:
    - 生活
---

> “Yeah It's on. ”


## 前言

就试试用git来保存书写内容吧。

[直接开始搭建过程吧 ](#build)



总之先试试用markDown写东西看看，感谢[Hux](http://huangxuan.me/)博客的模板，总是有时间就会在这个基础上修改前端内容看看吧，最初目的不过时为了试试git与jekyll。



<p id = "build"></p>
---

## 正文

接下来说说搭建这个博客的技术细节(在原作者的基础上=。=)。  

正好之前就有关注过 [GitHub Pages](https://pages.github.com/) + [Jekyll](http://jekyllrb.com/) 快速 Building Blog 的技术方案，非常轻松时尚。
前期基本根据[阮一峰](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)的教程进行。关于本地jekyll环境搭建参考[每个人都应该有一个Jekyll博客](http://www.tuicool.com/articles/ruMVjyN/).

jekyll其优点非常明显：

* **Markdown** 带来的优雅写作体验
* 非常熟悉的 Git workflow ，**Git Commit 即 Blog Post**
* 利用 GitHub Pages 的域名和免费无限空间，不用自己折腾主机
	* 如果需要自定义域名，也只需要简单改改 DNS 加个 CNAME 就好了
* Jekyll 的自定制非常容易，基本就是个模版引擎

##### 遇到的各种问题与建议
首先遇到的的问题是**gem镜像**的问题，**taobao Gems 源已停止维护，现由 ruby-china 提供镜像服务**，由于网络上的教程都比较古老，用默认源和淘宝的**各种报错！**顺带附上[使用链接](https://gems.ruby-china.org/).解决不了 **SSL 证书问题** 就用http.

---

配置的过程中基本就是 Git 的流程，环境建议直接使用git-pages,保证上传到github不会报错。


本地调试环境需要 `gem install jekyll`，前面已给出了如何搭建参考地址，远程使用**git bash** ,由于已经下载过github for windows,使用桌面端登录，就无须配置SSH。

关于路径问题，在上传到github上时，注意修改`_config.yml`下**baseurl**，保证与项目地址一致。如你在blog项目下保存，则设置为/blog.
注意以上，fork一个模板，就可以在github下使用blog了。






## 后记
就这样。

—— HZB 2016.4.20
