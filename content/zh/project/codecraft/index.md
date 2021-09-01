---
title: 金融风控的资金流水分析
summary: 2020huaweiCodeCraft
tags:
- Data Mining
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

通过金融风控的资金流水分析，可有效识别循环转账，辅助公安挖掘洗钱组织，帮助银行预防信用卡诈骗。基于给定的资金流水，检测并输出指定约束条件的所有循环转账，结果准确，用时最短者胜。

{{< figure src="diansai.jpg" title="" lightbox="true" >}}

以工业派开发板卡为处理中心，系统通过外接摄像头获取图像，并以OpenCV代码库作为程序开发接口，实现图像的读取与处理。

{{< figure src="show.jpg" title="" lightbox="true" >}}

系统进一步利用边缘检测、解码等方法进行二维码的识别与定位，实时输出检测目标的数量和运行方向，并通过串口实现了目标物体的位姿输出。

{{< figure src="show1.jpg" title="" lightbox="true" >}}

系统使用自主设计的一套串口通信协议，可以通过该协议在其他设备上进行不同目标的位姿读取，并将其转化为ROS话题发布，可以在RVIZ可视化软件中实时观测每个待检测目标的运动姿态与运动轨迹。

{{< video src="apriltag.mp4" controls="yes" >}}
