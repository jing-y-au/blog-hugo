---
title:       "Blog终于建成啦！"
subtitle:    "Github pages 建站框架大比拼"
description: ""
date:        2018-08-25
author: Jing
image:       ""
tags:        ["tech", "SSG"]
categories:  ["Tech" ]
---
# 序言

> 很久很久以前，在拜读阮一峰大师博客时，偶然发现了[用github pages搭建博客的介绍](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)，于是心中悄悄埋下了这样一颗种子。然鹅，一直忙啊忙啊没时间（我是不会承认自己的懒惰的），于是拖到了现在。至于为什么是现在，嗯，大概是最近鸡汤灌多了，突然就有了动力。 :P

废话少说，切入正题。基本概念在阮大师博客中已经介绍了，这里不再赘述。不过现在已经很多年过去了，想必已经有了更多更好的框架选择。于是进行了一番简单的市场调研。

# 高级web框架
如果你想要一个功能强大完备的博客平台，可以绑定数据库，可以后台管理，那么以下可能适合你：
## WordPress
使用PHP开发的开源框架，可做CMS使用，功能强大，插件众多。
## Django
使用Python开发的开源框架，详细介绍请戳[这里](https://developer.mozilla.org/zh-CN/docs/learn/Server-side/Django/Introduction).

# 轻量级
如果你只想要简简单单写点博客，不需要啥高级功能，一个简单易用的静态站点生成器（Static Site Generator，简称SSG）是最佳选择：
## Jekyll / Octopress
Jekyll是最老牌的框架，流行度最高，网上的资源也最多，Octopress是Jekyll基础上的再封装。需要安装使用Ruby。Build速度很慢。
## Hexo
用nodejs写的框架，优点是主题很漂亮，毕竟UI可是js的拿手好戏，插件也很多，速度比 Jekyll快很多，javascript爱好者的不二选择。缺点是依赖太多，升级会有很多坑。
## Hugo
用golang写的框架，速度非常非常快，官方文档里说是在毫秒级。部署简单，不需要安装依赖，直接二进制文件运行。缺点是因为是较新的框架，插件资源相对略少。

# 总结
如果你喜欢折腾，有各种定制化需求，用WordPress/Django。<br>
要简单好配置，用SSG：熟悉Ruby，选Jekyll，js爱好者就用Hexo，以上都不是，用Hugo。Hugo非常简单易用，上手极快。如果你不是像我一样有主题选择困难症的话，学习基本的安装构建只要半小时就能搞定，懒人用它妥妥的。本站就是使用Hugo搭建的。网上很多教程，我参考的是[这篇](http://nanshu.wang/post/2015-01-31/)。

心动不如行动，

> 挤需要三分钟，里就会像我一样，爱上杰款游戏 :DDDD

