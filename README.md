# WXAPK

微信安装改名后的 APK 补丁

## 问题背景
微信无法直接安装apk文件

这是因为，出于安全考虑，通过微信收到的.apk文件，会被重命名为.apk.1文件，导致无法直接安装。

## 使用方法
安装本应用以后，在微信里直接打开 .apk.1 文件，选择“用其他应用打开”，即可进入安装界面。

## 原理

通过 Intent Filter 去 handle apk.1 文件的意图，分发给应用安装器，over。

## 下载

1. 通过release 页面下载最新的包: 
[Releases](https://github.com/zhangzhibin/WXAPK/releases)

2. 通过Google Play下载 TwiceYuan同学的包，记得给好评哦
<a href='https://play.google.com/store/apps/details?id=com.twiceyuan.wxapk'>
  <img alt='下载应用，请到 Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/zh-cn_badge_web_generic.png' width='200px' />
</a>

## License 

MIT
