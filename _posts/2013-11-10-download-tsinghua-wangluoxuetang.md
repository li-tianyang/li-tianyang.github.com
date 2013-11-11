---
layout: post
title: "清华网络学堂下载工具"
description: ""
category: 
tags: []
---
{% include JB/setup %}

<img alt="网络学堂下载工具开始时候的界面" src="/img/posts/2013-11-10-download-tsinghua-wangluoxuetang/dl-wlxt-start.png" style="display: inline; height: auto; width: auto; max-width: 100%;" title="网络学堂下载工具开始时候的界面">


[这](https://addons.mozilla.org/en-US/firefox/addon/%E6%B8%85%E5%8D%8E%E7%BD%91%E7%BB%9C%E5%AD%A6%E5%A0%82%E6%89%B9%E9%87%8F%E4%B8%8B%E8%BD%BD%E5%B7%A5%E5%85%B7/)是一个可以用来下载以前上过的课的 Firefox 插件. 这个工具不下载本学期正在进行的课的网络学堂内容, 只下载以前的学期的课的网络学堂内容. 

下面介绍一下下载到自己电脑上的网络学堂的内容是什么样子的

### 总的下载目录 wlxt

所有下载内容都在 Firefox 默认的下载目录里面一个叫 wlxt 的目录里面

<img alt="Firefox 默认的下载目录里的 wlxt 目录" src="/img/posts/2013-11-10-download-tsinghua-wangluoxuetang/dl-wlxt-start.png" style="display: inline; height: auto; width: auto; max-width: 100%;" title="Firefox 默认的下载目录里的 wlxt 目录">

***

## FAQ

#### 为什么 "文化素质教育讲座" 这个课的 "课程讨论" 没有下载下来?

因为 "课程讨论" 里面不过滤用户插进去的 JavaScript, 所以有几个讨论导致这个工具不能正常下载

如果遇到别的课的 "课程讨论" 导致下载不成功, [这里](/post-more/2013-11-10-download-tsinghua-wangluoxuetang/kctl-js-injection.html)有一个临时的解决方案. 

[欢迎对这个工具进行改进](http://li-tianyang.com/2013/11/10/download-tsinghua-wangluoxuetang/#dev-dl-wlxt)

#### \*.csv 文件在 excel 里面打开的时候是乱码怎么办?

[http://www.itg.ias.edu/content/how-import-csv-file-uses-utf-8-character-encoding-0](http://www.itg.ias.edu/content/how-import-csv-file-uses-utf-8-character-encoding-0) 有更多的信息

#### \*.html 文件打开后是乱码怎么办?

可以把浏览器的编码换成 UTF-8 就不是乱码了

如果你不知到怎么把浏览器的编码换成 UTF-8, 可以到 [Google](http://google.com) 或者[百度](http://baidu.com) 上面搜 "换浏览器编码"

#### 能不能把文件名保存为正常的文件名?

由于不同的系统上对中文用的编码不同, 比如大部分 Linux 都是用的 UTF-8, 但是大部分 Windows 默认的中文编码不是, 所以这里进行折中都用了英文字母和数字作为文件名进行存储, 然后对应的信息在 \*.csv 文件中

如果你愿意改进的话, 请看[这里](http://li-tianyang.com/2013/11/10/download-tsinghua-wangluoxuetang/#dev-dl-wlxt)

#### 能不能让这个工具下载整个网络学堂内容的时间变得更短?

目前在下载的过程中没有并行的操作, 所以比较慢

如果你愿意改进的话, 请看[这里](http://li-tianyang.com/2013/11/10/download-tsinghua-wangluoxuetang/#dev-dl-wlxt)

#### 能不能把这个工具的整个用户界面和用户体验做得更好?

我没有在这个上面花太多时间, 所以目前这个工具的整个用户界面和用户体验并不理想

如果你愿意改进的话, 请看[这里](http://li-tianyang.com/2013/11/10/download-tsinghua-wangluoxuetang/#dev-dl-wlxt)

#### 能不能向这个工具里面增加更多的功能? 

请看[这里](http://li-tianyang.com/2013/11/10/download-tsinghua-wangluoxuetang/#dev-dl-wlxt)

<h4 id="dev-dl-wlxt">我能对这个这个工具的代码进行修改吗?</h4>

[https://github.com/tianyang-li/download-tsinghua-wangluoxuetang](https://github.com/tianyang-li/download-tsinghua-wangluoxuetang)

欢迎 fork 并且用 pull request 来改进这个工具

#### 别的问题

欢迎发邮件给李天阳 ([ty@li-tianyang.com](mailto:ty@li-tianyang.com))


