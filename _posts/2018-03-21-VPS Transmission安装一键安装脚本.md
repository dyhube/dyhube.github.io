---
layout:     post
title:      "VPS install Transmission & onekey script for PT"
subtitle:   "VPS一键安装Transmission"
date:       2018-03-21 12:00:00
author:     "Guang"
header-img: "img/post-bg-js-module.jpg"
tags:
    - Transmission
	- PT
---

### 1

执行如下代码

```shell
apt-get update

apt-get upgrade

apt-get dist-upgrade
```
### 2

执行如下代码

```shell
wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh
chmod +x bbr.sh
./bbr.sh
```
回车（重启）

### 3

再打开执行如下代码
```shell
wget --no-check-certificate -qO '/tmp/OneKeyForPT.sh' 'https://moeclub.org/attachment/LinuxShell/OneKeyForPT.sh'
```
### 4

```shell
bash /tmp/OneKeyForPT.sh -L 'ip地址' -U 'ID' -P 'password'
```
=====
注：在第四步中需要修改`ip地址`，也就是服务器的ip地址，设置登陆`ID`和`密码`，
=====