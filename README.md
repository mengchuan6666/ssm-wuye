# 基于ssm的物业小程序

**b站视频地址**：[https://www.bilibili.com/video/BV1aD4y1X77R](http://)

如果点赞数超过1000，给大家出详细教程！！

代码结构如下：

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195004_9ca9328b_7604956.png "屏幕截图.png")

## 1. 系统部署

参照IDEA部署后台项目的前置教程，安装部署项目所需的环境：[https://www.bilibili.com/video/BV1mi4y1L7JG](http://)

### 1.1导入项目

点击微信开发者工具菜单上的项目-导入项目

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195114_98f19099_7604956.png "屏幕截图.png")

填写项目信息

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195230_050197c2_7604956.png "屏幕截图.png")

点击右下角的导入按钮，导入小程序端的代码就成功了！

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195326_3f8852c5_7604956.png "屏幕截图.png")

打开idea，点击File-open

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195421_cc9831c6_7604956.png "屏幕截图.png")

找到后端代码所在目录

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195450_fd7f58c3_7604956.png "屏幕截图.png")

后端代码导入成功！

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195522_c0135f4c_7604956.png "屏幕截图.png")

找到后端代码文件中的shequ.sql文件

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195621_ded780e7_7604956.png "屏幕截图.png")

在navicat中点击新建数据库

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195652_f6d0c71f_7604956.png "屏幕截图.png")

新建数据库信息如下

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195719_fbdc7ecc_7604956.png "屏幕截图.png")

点击确定，数据库就建好了，右键点击数据库，选择运行SQL文件

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195811_06104d81_7604956.png "屏幕截图.png")

找到shequ.sql文件，点击开始

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195842_04105fb2_7604956.png "屏幕截图.png")

右键点击表，点击刷新

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/195933_8dc01ad3_7604956.png "屏幕截图.png")

就会出现项目需要的数据库表

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/200002_c2e042e0_7604956.png "屏幕截图.png")

一定要将后端代码中用户名和密码改成自己的

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/200124_23f7f3ba_7604956.png "屏幕截图.png")

点击启动即可！

## 2.系统介绍

非常简单易学的基于ssm的物业小程序项目，欢迎学习交流！

页面分为**首页**，**常用电话**和**我的**，不同的面板具有不同的功能!

### 2.1 小程序端

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/193010_b82621e5_7604956.png "屏幕截图.png")

首页有社区公告，报事报修，信息采集，生活缴费，二手置换等功能，在顶部有轮播图。

**社区公告**

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/193347_fceefb46_7604956.png "屏幕截图.png")

**报事报修**

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/193413_4e3a449e_7604956.png "屏幕截图.png")

**信息采集**

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/193437_d727dfa1_7604956.png "屏幕截图.png")

**生活缴费**

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/193510_b22a00d5_7604956.png "屏幕截图.png")

**二手置换**

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/193542_88032447_7604956.png "屏幕截图.png")

### 2.2 后台管理系统

程序启动起来后，访问**localhost:8080/SheQu/**即可访问后台管理系统

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/193932_3cee90c3_7604956.png "屏幕截图.png")

登录成功后进入后台管理的首页

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/194118_18407eb9_7604956.png "屏幕截图.png")

小程序管理

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/194147_11b48ad1_7604956.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/194307_9e6851ca_7604956.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/194325_b54d7af6_7604956.png "屏幕截图.png")

小程序数据查询

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/194221_f3773aa4_7604956.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/194237_3ae499c8_7604956.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1222/194250_65aee49c_7604956.png "屏幕截图.png")

**欢迎大家一起交流学习，共同进步。技术交流群，请加小孟微信：**

<div align=center><img width="250" height="250" src="https://images.gitee.com/uploads/images/2020/1219/203754_ef21dcd8_7604956.png"/></div>
