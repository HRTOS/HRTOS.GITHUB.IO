---
layout: post
title:  "HRTOS的使用方法"
date:   2018-11-06
excerpt: "HRTOS, 只因有你，所有伟大！."
project: true
tag:
- 使用 
- 工程
- 建立
- HRTOS
comments: true
---

![HRTOS](https://www.hrtos.com/ts/HRTOS.png)    
    

##  HRTOS的使用步骤
 下载了HRTOS最新版之后是不是很期待用一下呢？本文将介绍如何建立基于HRTOS的工程项目，使用前请确保正确安装了相应的编译器，默认为KEIL 4.我们就按KEIL为平台进行讲解。

<iframe src="https://ghbtns.com/github-btn.html?user=TaylanTatli&repo=Moon&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe>    
      
## 获取最新版HRTOS
* 方法1： [点击HRTOS](https://www.hrtos.com/download/HRTOS V2.30.rar)

* 方法2： 加入QQ群：523549975

* 方法3： 添加作者QQ：192444320（权威）   
     
就这样！

## 创建工程

### 1.解压文件

### 2.右键keil图标，选择打开文件所在位置，选择上一层后打开C51文件夹
{% capture images %}
	https://www.hrtos.com/ts/1.png
	https://www.hrtos.com/ts/2.png
	https://www.hrtos.com/ts/3.png
{% endcapture %}
{% include gallery images=images caption="分别将解压包目录下的INCLUDE文件夹下的文件和LIB文件夹下的文件复制到INC和LIB目录下" cols=3 %}

---
### 3.打开KEIL，新建一个工程。
    *启动后选择Project->New uVision project... 弹出会话框
    *给工程取好名字之后，选择保存或者回车
    *自动出现芯片选择会话框，选择合适的芯片，右侧出现该芯片的配置情况
    *选择好之后点击OK
    *之后询问我们是否将8051通用的文件添加到我们的工程下，这里我们选择 否（N）
{% capture images %}
	https://www.hrtos.com/ts/5.png
	https://www.hrtos.com/ts/6.png
    https://www.hrtos.com/ts/7.png
    https://www.hrtos.com/ts/8.png
{% endcapture %}
{% include gallery images=images caption="以上是建立工程的通用方法" cols=4 %}      

### 4.配置工程
    *查看是否弹出Project和Build Output
    *没有弹出按下图2所示图标选择相应控件
    *点击图3所示图标，弹出对话框如图4所示
    *修改Memory Model选择第二个，如图5所示
    *选择Output栏，选中Create HEX File，如图6所示
    
{% capture images %}
	https://www.hrtos.com/ts/10.png
	https://www.hrtos.com/ts/11.png
    https://www.hrtos.com/ts/12.png
    https://www.hrtos.com/ts/13.png
    https://www.hrtos.com/ts/15.png
    https://www.hrtos.com/ts/16.png
{% endcapture %}
{% include gallery images=images caption="以上是配置工程的方法" cols=6 %}   

### 5.在工程中添加相关的文件
  注意手动添加HRTOS.LIB到工程。
### 6.编译、链接

### 7.下载到51单片机

## 还有其他问题？
 欢迎加QQ群与大家交流！！！
