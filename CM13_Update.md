# CM13 for SM-G9008V 升级指南

#### 升级准备
* CM13安装包
* 对应的CM12.1 Snapshot 版本
* Xposed框架，SuperSU安装包
* GMS安装包

#### 升级过程中注意的事项
1. 必须双清，SDK不同导致CM12.1版本的很多都会在CM13下报错
2. 直接升级CM13在目前是会产生没有4G信号的问题，所以必须在CM12.1的前提下升级
3. Google Play Services的安装包获取在网址
> [Opengapps](http://opengapps.org)
> 对应SM-G9008V的版本是ARM

4. GMS的安装必须在CWM中紧接着CM13安装后安装，否则进入CM13后会报错。
5. Xposed Framework 安装必须先安装相应的APK文件再从CWM中刷入ZIP

####    CM13发现的问题
* 如果开启相册之后就锁定屏幕后，会产生在索苹界面开启相机白屏的现象。

