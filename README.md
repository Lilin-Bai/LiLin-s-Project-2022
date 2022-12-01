# Arduboy
Arduboy Gameplayer(ATMEga32U4) with Flash

-----

### 项目概述

* 项目根据海外现有开源项目加以改进添加128M的Flash，相较于原版的只能存一个游戏有实质上的升级，并且由于ATmega32u4的强悍性能，可以畅玩很多游戏，游戏体验极佳。
* 凑巧看到了“RT6150A/B”这款升降压芯片，被用在了树莓派上，看来数据手册，这颗芯片，除了贵，没毛病。参考视频：（B站UP主：工科男孙老师）**[RT6150A/B](https://www.bilibili.com/video/BV1jF411J7SW/?share_source=copy_web&vd_source=dce9f033d82cd7377d3bfe0759a57f75)**
* 项目过程文稿演示视频已上传至哔哩哔哩，链接直达：**[Arduboy](https://www.bilibili.com/video/BV1nM41167SL/?share_source=copy_web&vd_source=dce9f033d82cd7377d3bfe0759a57f75)**

- - -

### 制作与调试

* 项目已基本完成，外观有两种选择，一是用两片PCB充当外壳，更具科技感，无需3D打印（我个人更喜欢这一款），另一种就是单片的PCB，使用3D打印外壳，两款成品的体积都十分小巧，平成揣在兜里几乎觉不出来（不是那种紧身的衣服），两款成品图片都在下方，各位留意。
* 双PCB效果
![双PCB款成品图](//image.lceda.cn/pullimage/1RzKfSiqaekETwPMYNl15Yt9gevkNn1vnrwHq0hA.png)
* 3D打印外壳款
![3D打印外壳款成品图](//image.lceda.cn/pullimage/M8PdM27UQ1782Sgz2E78Jp0X7lqPBRv53Vc610Dl.png)

- - -

### 烧录及上传

* 使用Arduino进行烧录，参数如下图
* 注：若使用Arduino UNO作为烧录器需选择“Arduino as ISP”
* 工程附件中有bootloader，游戏文件，及游戏文件上传程序

- - -

### 3D渲染图及成品图

* 双层款
![上层](//image.lceda.cn/pullimage/ekz9SZYdGQJuDov3OUdLVOKZw4jfHreRxJWd1qXM.png)![下层](//image.lceda.cn/pullimage/ZLa2zPIwDX1Gd8DOxbsIALL2sMUUU9MrYAmxYcfp.png)
* 双层款（拼板）
![拼板 正](//image.lceda.cn/pullimage/0qs8Jucl0C55GzdOzN8H6U1xTZGbxdnzOYnQLkdy.png)![拼板 反](//image.lceda.cn/pullimage/cH9AwfZaXUWJBddLN5Ze1SGD3K9gPxDhGxeGVjUc.png)
* 3D款
![3D款 PCB 正面](//image.lceda.cn/pullimage/u00YIyQMxPbA91oh1IcrY6wahZtikR9IBwPI8Gi5.png)![3D款 PCB 反面](//image.lceda.cn/pullimage/BZl3ir8slT67T7H9BvIp6OBPATamUR0zqiUDEatA.png)

- - -

### 备注

* 参考：**[Arduboy官网](https://www.arduboy.com)**
* 项目一并开源至Github：**[项目主页](https://github.com/Lilin-Bai/LiLin-s-Project-2022)**

- - -

### 声明

* 本项目PCB及原理图开源协议：CC-BY-NC-SA
* 本项目源码开源协议：GPL3.0

- - -

### 开源文件（附件）介绍

* SCH_Arduboy+V5.0.pdf——PDF原理图
* arduboy3k-bootloader.hex——Bootloader
* 300个游戏.bin——游戏文件
* Arduboy-uploader.part1&2.rar——游戏上传程序
