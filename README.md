android-push
==========================================

## 一、说明

单通道多App push系统以service方式运行，如果一个手机安装了多个集成push的应用，只有一个service实例运行(不会每个应用都开启一个后台服务)，即多个应用共享一个push通道，这样的设计目的是：减少手机运行的进程数量，减少内存使用量，减少手机的耗电量，减少网络流量。


## 二、原理图 

![github](https://github.com/zz7zz7zz/android-push/blob/master/1.jpg "附图一")




[欢迎访问我的CSDN博客](http://blog.csdn.net/zz7zz7zz)<br />



