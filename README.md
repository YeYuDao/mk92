# mk92
编程必备基础-音视频小白系统入门课
编程必备基础-音视频小白系统入门课
[![下载地址](https://img.mukewang.com/szimg/5fce102a095f90c005400304.jpg "下载地址")](https://51xueit.vip "下载地址")
[下载地址](https://51xueit.vip "下载地址")
### 第1章 课程导学与准备工作 

#### 本章主要介绍为何要带大家学习一个音视频初级入门课程，本课程中不仅系统的讲解了音视频到底是如何工作的，还会将音视频原理与实战相结合，讲解学习阶梯和实现思路，之后会为大家介绍本课程内容具体安排，最后给出如何学好这门课程的一些学习建议。希望大家都能通过这门课程，学有所成，学有所归。...
1-1 课前必读（不看会错过一个亿）

1-2 课程介绍及学习指导 (18:49)


### 第2章 音视频环境基础 

#### 本章会讲解学习音视频课程之前必要的基础知识，如Linux常见命令以及环境变量的设置等。在之前的课程中，有很多同学提出的问题都是Linux的基础知识问题，尤其是在Windows下工作的同学，因此这部分知识对于 Windows 同学来说至关重要。...
2-1 音视频应用的场景 (13:00)

2-2 推流中断与画质不精晰的解决办法 (06:37)

2-3 Linux基础知识-1 (15:16)

2-4 Linux基础知识-2 (18:39)

2-5 巩固Linux基本命令（熟练可跳过） (17:47)

2-6 巩固vim的简单使用（熟练可跳过） (05:29)

2-7 Mac:Linux环境变量的含义与设置 (16:44)


### 第3章 在不同的系统上编译 ffmpeg

#### 本章会讲解在不同操作系统下如何编译安装ffmpeg，重点是讲解 Windows下编译 ffmpeg的方法等。实际上，在Windows上编译 ffmpeg 一直是一个难点，有很多同学都卡在这个问题上，因此通过本章节的内容就可以轻松解决你的问题。
3-1 Mac或Linux下编译安装ffmpeg (19:23)

3-2 Windows下编译ffmpeg的几种方式 (08:49)

3-3 Cygwin环境的搭建 (13:09)

3-4 Cygwin下安装ffmpeg (14:42)

3-5 msys2环境的搭建 (06:22)

3-6 msys2+mingw编译ffmpeg (05:56)

3-7 msys2+vs编译ffmpeg (12:21)


### 第4章 C语言回顾

#### 本章会带领大家回顾C语言必要的基础知识，重点讲解C语言中的指针等难点内容，帮助大家为后续学习开发做好准备。
4-1 C语言的HelloWorld (13:14)

4-2 C语言中的基本类型和逻辑运算 (12:13)

4-3 C语言中的高级类型：数组、结构体和枚举类型 (17:13)

4-4 C语言中的指针 (09:15)

4-5 C语言中指针的使用 (11:30)

4-6 内存管理与分配 (11:09)

4-7 条件判断与循环 (10:15)

4-8 C语言中的函数 (11:06)

4-9 C语言如何操作文件 (16:27)


### 第5章 音频基础知识

#### 本章将带大家学习音频的基本原理（如声音是如何产生的，模拟信号是如何转为数字信号、音频的三要素等信息）。这些信息的掌握，对大家今后处理音频相关的问题时有切实的帮助，如当你播放PCM数据时声音不对，那一定是采样率、采样大小或通道数没有设置正确的原因。...
5-1 音视频处理流程 (10:29)

5-2 声音是如何被听到的 (09:56)

5-3 声音的三要素 (09:06)

5-4 模数转换 (05:32)

5-5 PCM与WAV (14:45)


### 第6章 【实战】音频采集

#### 本章向你介绍了如何通过ffmpeg API进行音视频数据采集。在讲解过程中，将手把手的带着你编写每一行代码，并对每个用到的 API 参数做了详细介绍。在本章的最后，你还将看到如何将采集到的音频数据录制成文件。相信这对有录制要求的同学也会有很大帮助。...
6-1 通过命令方式采集音频数据 (09:37)

6-2 swift语法一 (09:55)

6-3 swift语法二 (10:19)

6-4 创建Mac App (11:57)

6-5 创建 Button (11:27)

6-6 swift调用C语言 (07:13)

6-7 Mac App中引入ffmpeg库 (15:18)

6-8 打开音频设备 (17:11)

6-9 从音频设备中读取音频数据 (15:05)

6-10 代码优化 (10:59)

6-11 录制音频数据 (10:23)

6-12 通过界面来控制开启或关闭录制 (18:35)

6-13 采集音频数据命令

6-14 打开设备

6-15 音频设备参数可以修改吗？

6-16 如何获得不同系统下音频设备参数？

6-17 采集音频数据时总是返回-35, 这是什么原因？


### 第7章 音频编码原理

#### 本章向你介绍多种音频编码器（如 AAC, OPUS, speex等），并对各种不同的编码器进行比较，并在众多的编码器中重点向你介绍了 AAC 编码的以及它的不同级别的特性，同时还向你介绍了 AAC 数据头（ADTS） 的详细格式。
7-1 音频有损压缩技术 (13:03)

7-2 音频无损压缩技术 (07:18)

7-3 几种常见编解码器的比较 (09:13)

7-4 AAC编码器介绍 (10:02)

7-5 ADTS格式 (09:55)

7-6 通过ffmpeg生成AAC数据 (13:04)


### 第8章 【实战】音频编码

#### 本章以AAC编码为例，向你详细介绍了如何对PCM数据进行重采样以达到AAC 编码的要求，然后讲解了如何通过ffmpeg获取AAC编码器，如何设置编码参数，并最终实现编码的过程。在本章的最后，还将向你详细的介绍如何对代码进行优化以达到更好的编码风格。...
8-1 什么是音频重采样 (11:53)

8-2 实战音频重采样1 (18:00)

8-3 实战音频重采样2 (16:40)

8-4 创建AAC编码器1 (18:19)

8-5 创建AAC编码器2 (06:59)

8-6 编码使用的输入输出数据 (16:36)

8-7 AAC编码器编码1 (12:21)

8-8 AAC编码器编码2 (13:46)

8-9 代码优化1 (16:58)

8-10 代码优化2 (16:42)

8-11 代码优化3 (17:05)


### 第9章 视频基础知识

#### 本章将讲解视频的基础知识（像素、RGB、分辨率等）、视频帧（图像）与显示器之间的关系。重点讲解YUV数据格式（如YUV4:4:4､YUV4:2:2､YUV4:2:0等），并让你掌握 YUV 与RGB 之间的转换以及视频未编码码流该如何计算。
9-1 图像的基本概念 (05:44)

9-2 屏幕显示器 (08:17)

9-3 码流的计算 (09:21)

9-4 图像的显示 (08:37)

9-5 什么是YUV (08:54)

9-6 YUV的常见格式 (08:43)

9-7 YUV的存储格式 (10:57)

9-8 YUV实战 (18:41)

9-9 实战从视频设备上采集数据1 (13:18)

9-10 实战从视频设备上采集数据2 (11:46)


### 第10章 H264编码原理

#### 本章将介绍H264 的编码原理，这部分是本门课中最关键的知识点，通过本章的内容你不仅可以知道H264是如何对视频进行编码的，还可以了解H264的数据结构。通过这些知识的学习，你就可以解决很多常见的视频疑难问题，例如为什么播放器可以知道视频的分辨率，为什么视频会出现花屏，为什么会出现卡顿等等。...
10-1 H264压缩码率与GOP (13:00)

10-2 H264中的I帧P帧和B帧 (14:57)

10-3 H264中的宏块 (10:28)

10-4 帧内压缩技术 (12:20)

10-5 帧间压缩技术 (13:34)

10-6 H264无损压缩及编解码处理流程 (12:56)

10-7 H264码流结构 (19:03)


### 第11章 【实战】视频编码/解码

#### 本章将重点介绍如何对采集到的视频数据进行H264编码。同理，只要你学会了如何进行 H264编码，就会知道 H265/VP8/VP9如何进行编码。除此之外，你还将了解一些H264的重要编码参数，在不同的应用场景中掌握该用怎样的参数，这在我们实际工作中是至关重要的。...
11-1 H264中的profile和level (11:23)

11-2 H264SPS中的重要参数 (12:11)

11-3 H264PPS与Slice-Header (07:31)

11-4 H264分析工具1 (14:44)

11-5 H264分析工具2 (14:35)

11-6 实战打开视频编码器1 (17:37)

11-7 实战打开视频编码器2 (12:12)

11-8 实战准备要编码的数据 (14:16)

11-9 实战NV12转YUV420P (15:48)

11-10 实战H264编码1 (15:59)

11-11 实战H264编码2 (13:56)

11-12 x264参数详解 (18:22)


### 第12章 【实战】RTMP传输

#### 在本章中你将首先详细了解 RTMP/FLV协议，然后利用librtmp 开源库将之前编码好的音频数据（AAC）与 编码好的视频数据（H264）生成 RTMP 流并推送到 CDN 流媒体服务器上，从而实现真正的娱乐直播。
12-1 RTMP连接的建立 (11:56)

12-2 创建RTMP流 (07:55)

12-3 RTMP消息 (17:27)

12-4 RTMP抓包分析 (13:30)

12-5 FLV协议 (08:55)

12-6 FLV协议分析器 (13:39)

12-7 推流程序的骨架 (22:08)

12-8 打开FLV文件 (08:22)

12-9 连接RTMP流媒体服务器 (11:08)

12-10 向流媒体服务器推流 (13:23)

12-11 从FLV文件中读取tag数据1 (16:36)

12-12 从FLV文件中读取tag数据2 (18:39)

12-13 调试与优化 (17:45)


### 第13章 【实战】CDN 实现商业娱乐直播

#### 在本章中我们将按照由浅入难的顺序，即先介绍nginx实现流媒体服务器，然后讲解 SRS 实现流媒体服器，最后讲解在真正的商用产品中是如何通过 CDN云服务来实现大并发，通过本章的学习，你开发的产品将从 Demo 升级为真正可用的产品。...
13-1 泛娱乐化直播系统架构介绍 (12:55)

13-2 本机搭建RTMP服务 (17:58)

13-3 SRS流媒体服务器简介 (10:31)

13-4 SRS单机布署 (17:04)

13-5 RTMP中的URL与VHOST (07:13)

13-6 SRS实现集群布署 (19:07)

13-7 CDN网络 (12:10)

13-8 阿里云视频直播 (12:22)

13-9 真实的直播架构是怎样的 (16:01)


### 第14章 课程总结

#### 本章将带大家回顾总结课程重点难点，在课程问答区李超老师等着与你进一步交流，有问题欢迎大家到课程问答区提问。
14-1 课程总结 (16:41)


[下载地址](https://51xueit.vip "下载地址")
