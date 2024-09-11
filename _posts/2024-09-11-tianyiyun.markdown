---
layout:     post
title:      "天翼云重装Linux系统"
subtitle:   " \"Hello World, Hello Blog\""
date:       2024-09-11 12:00:00
author:     "少年帅哒"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - 系统
---

> “两条命令装系统”


非常简单，使用github的一键脚本


1.管理员运行cmd
2.输入命令安装脚本
certutil -urlcache -f -split https://jihulab.com/bin456789/reinstall/-/raw/main/reinstall.bat
3.选择要重装的系统
reinstall.bat系统名版本号
比如装Ubuntu系统
reinstall.bat ubuntu 22.04
里面会显示能装的系统，复制完命令记得点回车
4.之后会有一个确认
直接 y回车
准备完成后会让你输入
shutdown /r /t 0
重启
5.重启后会出现一个选择界面，直接选择你要装的那个系统，然后回车，之后等待安装完成
登录账号root
密码123@@@
6.如果出问题卡住了，不知道怎么搞了，直接点天翼云电脑上面的小扳手里的偏好设置，直接系统重装
7.今天体验了一下天翼云电脑刷成Ubuntu系统装上了图形化界面感觉比windows还卡
