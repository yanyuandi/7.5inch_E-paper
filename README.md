## 桌面多功能E-paper
![image](jpg/109A0671.jpg)

### 项目简介
此项目使用ESP32驱动7.5寸三色墨水屏显示丰富的信息，如果感兴趣，请继续阅读，下文介绍如何使用此项目代码

### 需要的环境
- 一个远程服务器，需要安装LNMP环境，同时安装thinkPHP6.1
- 一个域名，用来转化各种api以及访问更新待办事件的上位机页面
- Arduino IDE

### 使用的硬件
- ESP32 WROVER开发板以及屏幕转接板 （闲鱼搜记得带马扎 可以购买现成pcb）
- 一块7.5寸三色墨水屏（使用GxEPD2_750c_Z08驱动）
- 3.7v锂电池

### 7.5inch_Multifunctional_E-Paper文件夹
此文件夹中为驱动墨水屏主要代码，包含了
