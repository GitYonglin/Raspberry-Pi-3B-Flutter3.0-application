# Raspberry Pi 3B 运行 Flutter3.0 记录
 - 这个是在Raspberry Pi 3B 中编译的
 - 编译了很多次才成功
 - 能运行但是很卡
## 系统：
- https://downloads.raspberrypi.org/raspios_lite_arm64/images/raspios_lite_arm64-2022-04-07/2022-04-04-raspios-bullseye-arm64-lite.img.xz
  - Raspberry Pi OS Lite
  - Release date: April 4th 2022
  - System: 64-bit
  - Kernel version: 5.15
  - Debian version: 11 (bullseye)
  - Size: 270MB
  - Show SHA256 file integrity hash:
  - Release notes
## flutter
  Flutter 3.0.1 • channel stable • https://github.com/flutter/flutter.git
  Framework • revision fb57da5f94 (13 days ago) • 2022-05-19 15:50:29 -0700
  Engine • revision caaafc5604
  Tools • Dart 2.17.1 • DevTools 2.12.2
## 依赖安装
- https://flutter.cn/docs/get-started/install/linux
``` bash
# 官方提到的需要安装的依赖
sudo apt-get install clang cmake ninja-build pkg-config libgtk-3-dev liblzma-dev
# 需要安装这个才可以用运行
sudo apt-get install xorg
```