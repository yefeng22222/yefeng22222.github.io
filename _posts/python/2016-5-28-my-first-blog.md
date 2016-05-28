---
layout: post
published: true
title: 这是我的第一个博客开始的地方
description: stay foolish，stay hungry
---  


## 前述
本人北邮研究生，可以说是彻彻底底的渣硕一枚，现研一。本科说实话比较水，不知是否适合读研究生，都说读研好，就读了。一直想改变自己的现状，但总是一些基础性的学习，不知何去何从。github博客不是用来谈天说地的，勇者无畏，就这样开始自己的行程。什么也没做，先说一下自己博客的搭建吧，技术小白一个，参考别人的博客与各种解决方法。  
note：本人使用的是ubuntu系统15.10。


## 1.  github相关操作

[github](https://github.com/)，简单来说，就是一个开源代码库。里面可以找到你需要的大量的程序资料。相关介绍和使用入门，自己百度就好，有大量的教程可供参考。  
Tips：网上的教程最好多看看近期的，因为页面更新换代，很多东西很难找，不过多浏览一下页面选项以及功能还是蛮重要的。


### 1.1  github博客搭建

github[博客搭建](http://blog.csdn.net/renfufei/article/details/37725057)，这是最简单的操作，照着步骤一步一步来救可以了。  
git：


    //这里是一些git代码操作  
    git clone https://github.com/username/username.github.io  
    git add --all  
    git commit -m "Initial commit"  
    git push -u origin master


具体意思，也是刚刚接触，多看看[git参考文档](http://git.oschina.net/progit/)

### 1.2   github 模板

github[模板](https://github.com/yefeng22222/yefeng22222.github.io)，参考的别人的文章，搭建的。这里说一下可能出现的bug  
1. 安装jekyll，retext，git-all时，出现runit未配置的错误，网上查了好久最终的得以解决，ubuntu15.10自身bug。  
    ```git：  
        //解决方法：  
        sudo apt-get purge runit  
        sudo apt-get purge git-all  
        sudo apt-get purge git  
        sudo apt-get autoremove  
        sudo apt update  
        sudo apt install git  
        sudo apt-get install jekyll  
        sudo apt-get install retext  
    ```  
2. 没啥好说的了，试着发表自己的第一编博文。p：正在试，不知能否成功？


## 2.  提高自己的效率

参考[博文](http://litaotao.github.io/words-to-share-with-the-young)，效率问题疑惑  
[markdown](http://www.ituring.com.cn/article/23).语法简单入门


## Ending
