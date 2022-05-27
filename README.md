# OpenStick
msm8916 4g网卡的逆向工程和主线移植

### 完全开源，但是禁止商用！

* 商用行为包括： 
  * 售卖原本免费开放下载的所有系统镜像及其衍生品。
  * 将通过HandsomeMod构建系统构建的产物通过收费进行发布。
  * 大规模批量售卖搭载OpenStick Linux的设备。
* 本项目的所有涉及高通firmware的二进制文件仅供学习用途，并服从高通firmware原本的[License](https://github.com/HandsomeMod/qcom-firmware/blob/main/LICENSE)，若不当使用造成任何法律问题后果自负。

目前的进度

* 完成了msm8916-mainline部分特性向5.10稳定内核的移植，初步完成了HandsomeMod（openwrt）的移植，能够通在对设置调整最小的情况下完成基本功能。
* 完成了绝大多数功能在主线中的驱动，并运行postmarketOS。
* 在Debian中驱动了msm8916网卡所有的外设。
* 完成了Modem在HandsomeMod中的驱动。
* 支持在windows平台下的烧写。

尚未完善的

* 视频编码器由于某些原因无法正常工作。
* 部分wifi型号由于原厂切卡逻辑不清晰暂不支持Modem。
* 详见wiki。

## 刷机包

* 这个刷机包会覆盖原机的分区表（删除了没用的分区，大概会给rootfs腾出3G多的空间）和引导程序，不再兼容安卓系统，请使用时做好备份。我也不会提供回去的办法。
* 包在release里面。

## WIKI 

​     wiki正在建设之中，欢迎各位大佬投稿或者star！！

  [WIKI地址](https://www.kancloud.cn/handsomehacker/openstick/content)
