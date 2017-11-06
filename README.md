# Android-FastBoot

流程：
adb reboot bootloader 开机状态直接进入 刷机模式
E:\sdk\platform-tools  fastboot.exe   此目录下
fastboot oem unlock
fastboot flashing unlock
fastboot devices
解压镜像文件
F:\AndroidImg\Nexus6p\8.0\angler-opr6.170623.019\flash-all.bat 执行此脚本，一键刷机

刷bootloader版本：
fastboot flash bootloader bootloader-shamu-moto-apq8084-72.04.img

镜像位置：
https://developers.google.com/android/images

中国镜像位置：
https://developers.google.cn/android/images
 
指导：
http://www.360doc.com/content/16/1223/16/36367108_617098516.shtml
