# 北京大学浅水模式 #


## 1. 概述 ##

北京大学浅水模式（简称 PKU-SWM）项目，是由闻新宇与贾喆于2011-2014年建立的。我们致力于开发并维护一套易于使用的（Code Less）、运行更快的（Run Faster）、能胜任更多研究工作（Achieve More）的浅水模式代码。我们发展模式的初衷是为科研和教学服务，同时开放给中国的大气科学团体使用。模式代码服从GNU GPL v3协议。

## 2. 模式特点 ##

  * Arakawa's C-grid with h/u at poles, or v at poles
  * support of Open-MP parallel computing
  * support of CUDA parallel computing
  * 2nd order spatial discretization
  * 2nd/3rd/4th Runge-Kutta and Adams-Bashforth integration schemes
  * support of ocean-land mask file
  * FFT polar filter
  * Shapiro 2nd/4th/8th order non-linear filter
  * I/O with netCDF format

## 3. 获取代码 ##

### Latest Version ###

如果您使用 Unix/Linux/MacOS 等 Unix-like 类型的操作系统，可以使用如下命令行下载当前最新版本的代码：

```
svn checkout http://pkuswm.googlecode.com/svn/release/latest pkuswm_latest
```

### Old Version ###

如果您想下载老版本的代码，需先查看本网站 Source > Browse 栏目 /svn/release 目录下都有哪些老版本。再用如下命令下载相应的版本：

```
svn checkout http://pkuswm.googlecode.com/svn/release/[希望下载的老版本] pkuswm_old
```

请原谅由于 Google Code Project 项目安全政策的约束，您只能通过上述方法用 SVN 工具来下载我们的代码，而不能通过点击直接下载。