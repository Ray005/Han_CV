# PLC温度监控 使用Python TK编写的上位机

- 2021年初（本人的本科三年级）完成的项目，从PLC梯形图编码到PC端Python上位机编码都是我的工作内容。
- 基本介绍：使用PLC读取Fluke激光温枪，再使用串口发送，通过LoRa串口透传，传输至有50m远且有水泥墙壁，强电磁干扰环境（由感应加热引起）下的PC电脑中。PC中运行着由Python TK编写的上位机，用于实时监控温度情况。
- 目前仍运行于河北省邢台市和阳轧辊机械有限公司。

## 项目展示


<div style="position: relative; padding: 30% 45%;">

<iframe style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;" src="https://player.bilibili.com/player.html?aid=313506264&bvid=BV1AP41127YL&cid=1125913967&page=1&autoplay=0&danmuku=0" frameborder="no" scrolling="no">

</iframe>

</div> 【Project#1】p1西门子PLC传输至办公室电脑 站点：Bilibili

<div style="position: relative; padding: 30% 45%;">

<iframe style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;" src="https://player.bilibili.com/player.html?aid=486102541&bvid=BV17T411t7HM&cid=1125918935&page=1&autoplay=0&danmuku=0" frameborder="no" scrolling="no">

</iframe>

</div> 【Project#1】p2 python监控上位机 站点：Bilibili



## 项目细节

监控的流程图为

![监控系统PLC程序流程图](PLC%20Temp%20Monitor%20Coded%20with%20Python%20TK%2085d8cb56f1b8494f9b75a044cd99392c/Untitled.jpeg)

监控系统PLC程序流程图

使用的LoRa透传模块型号：

![Untitled](PLC%20Temp%20Monitor%20Coded%20with%20Python%20TK%2085d8cb56f1b8494f9b75a044cd99392c/Untitled.png)