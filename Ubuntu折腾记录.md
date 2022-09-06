# Ubuntu折腾记录

# 写在前面
```
因鄙人有多余的笔记本用于~~折腾~~研究，且VMware对MacOS支离破碎支持早已伤透我的心，故决定直接分出50GB空间安装Ubuntu。
```
# 准备工作

因鄙人已有用U盘安装Win及Majaro Linux的经验，故选择使用U盘安装Ubuntu。
本次安装Ubuntu的设备是Dell Inspiron 5310。

# 下载镜像与工具

前往[Ubuntu官网](https://ubuntu.com/download/desktop)下载最新x86版本镜像
下载[Balena Ether](https://www.balena.io/etcher/)，为了方便起见，本次选择Portable版本。
<p align="center">
  <img src="https://i.ibb.co/48vByty/2022-09-06-20-48-09.png">
</p>

# 写入镜像

打开Ether并按要求选择镜像和要写入的硬盘，一路next直接写入。

# 配置Bios

关闭电脑，短按开机键，logo出现后狂按F2键进入Bios，在Boot configuration下关闭Secure Boot（Secure Boot类似于安卓的Bootloader Lock，会限制运行第三方系统）。

调整启动顺序，将U盘放在启动列表首位。

# 启动Ubuntu

重启电脑，Bootloader会自动启动Ubuntu菜单，选择第一项以进入系统。

# 安装

选择语言为简中，一路next就ok了，安装完后记得重启。