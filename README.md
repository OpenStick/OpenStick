# OpenStick
msm8916 4g网卡的逆向工程和主线移植

### 完全开源，但是禁止商用！

目前的进度

* 完成了msm8916-mainline部分特性向5.10稳定内核的移植，初步完成了HandsomeMod（openwrt）的移植（但是luci里modem还用不了），目前还在对代码进行清理，Openstick的支持将会在年前加入。
* 完成了所有功能在主线中的驱动，并运行postmarketOS。
* 在Debian中驱动了这个网卡所有的外设。
* 完成了modem在HandsomeMod中的驱动（这个包可能会鸽~）
* 支持在windows平台下的烧写



## 刷机包

* 这个刷机包会覆盖原机的分区表（删除了没用的分区，大概会给rootfs腾出3G多的空间）和引导程序，不再兼容安卓系统，请使用时做好备份。我也不会提供回去的办法（没研究过：p）
* 包在release里面。



## WIKI 

​     wiki正在建设之中，欢迎各位大佬投稿或者star！！

  [WIKI地址](https://www.kancloud.cn/handsomehacker/openstick/content)
