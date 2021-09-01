---
title: 分布式SLAM系统
summary: 服务机器人云服务关键技术
tags:
- Robotics Navigation
date: "2019-08-27 T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
基于ROS2的分布式SLAM系统的设计目标是能够让底层机器人在室内环境中进行实时建图，此过程涉及网络通信、数学几何、概率估计以及计算机技术等多学科知识交叉，需要掌握ROS2的系统特性与设计流程，熟悉机器人的运动控制规律和SLAM相关建图算法，梳理和搭建整体的知识框架。

基于ROS2的SLAM系统的实现任务主要包括底层双轮差速实验平台的搭建和系统程序框架的调试，实验平台可以在手柄的控制下，在室内未知环境中完成定位和建图的工作，能够适应有损网络环境，保证数据安全可靠。

{{< figure src="AAAA.jpg" title="" lightbox="true" >}}

基于ROS2的分布式SLAM系统架构，主要由四部分组成：云端服务器、中间管理层、全局数据空间、底层机器人。系统架构层次简洁，且具有良好的实用性，所有基于ROS2开发的机器人和支持ROS2系统的计算设备都可以通过统一的接口、按照结构层次接入系统中。

{{< figure src="STRUCTURE.jpg" title="" lightbox="true" >}}

双轮差速运动平台的底层硬件功能模块组成如图。双轮差速运动平台配备16.8V锂电池，用于电源供给，通过逐级稳压电路分别为12V直流减速电机、通信电路和3.3V工作电压的STM32主控芯片供电。底层配有串口通信、RS232通信等三种不同形式的通信模式，以适应不同环境中的通信需要。OLED七针显示屏可实时显示程序参数的数值，便于后期功能调试。

{{< figure src="1AS.jpg" title="" lightbox="true" >}}


基于ROS2的代码结构对ROS1的可执行程序进行更新和移植，系统软件节点分布图如图所示。

{{< figure src="34.jpg" title="" lightbox="true" >}}

{{< figure src="33.jpg" title="" lightbox="true" >}}

{{< figure src="32.jpg" title="" lightbox="true" >}}

{{< figure src="2222.jpg" title="" lightbox="true" >}}

场景实拍和环境结构布局如图所示。


{{< figure src="MAPPING.jpg" title="" lightbox="true" >}}

通过实验对比，基于ROS2的分布式SLAM系统能够高效地完成定位与地图构建的工作任务，并且建图效果和已经得到广泛应用的ROS1系统框架基本一致。另外，ROS2使用DDS的节点发现机制代替了ROS1的节点管理器，无需启动ROS_Master的布局操作，在多机器人系统应用中，将会省略诸多复杂的启动步骤，大大提高系统的工作效率和用户使用体验。

{{< video src="N1.mp4" controls="yes" >}}

{{< video src="N2.mp4" controls="yes" >}}