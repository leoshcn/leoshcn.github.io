---
layout: post
title:  "非程序员部署Jekyll笔记"
date:   2015-01-01 00:14:12 +0800
category: jekyll
author: Leo
---

折腾了很长时间，最后还是在我自己的笔记本电脑上成功部署了 Jekyll.
作为一个不会写代码的Geek，实属不易啊。
赶紧记下来要点，否则重装电脑之后又完蛋了

* 主要还是参考了Yanping 的这篇[视频教程](http://yanping.me/cn/blog/2013/08/11/github-pages-step-by-step-video/)
* Windows 安装需要注意安装 Python - 别忘记重启电脑
* Python的路径要手动添加到windows 环境变量
* 我的代码高亮程序还是要换成 Rouge 才行，系统默认的 Pygments 还是有问题

### 注意几个关键的Jekyll 命令
`Jekyll build` - 根据配置在 _site 下生成网站，可以加--watch 参数实时更新

`Jekyll serve` - 基本和上面的一致，唯一不同是同时在本机4000端口提供一个访问服务，一般用作本机调试
