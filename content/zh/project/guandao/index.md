---
title: 管道机器人
summary: 服务机器人云服务关键技术
tags:
- Control system
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

机器人的主要创新点：首先，设计了独立驱动三足对称设计，在适应各种管径的同时，提高了机器人的运动能力；其次，设计了多场景的运动保障系统，保障机器人稳定运行；最后，卡尔曼滤波和模糊逻辑器等算法提高了环境检测的准确性。

{{< figure src="first.jpg" title="" lightbox="true" >}}

机器人采用三足对称的履带式独立驱动设计，能够适应大型管道管径的变化。大功率电机驱动板和电源管理系统保障机器人在管道内的安全稳定运行； 模糊算法和能源模型的建立，能够帮助机器人精准灵活的控制和提高续航能力；电压环、电流环、压力环等反馈电路实现机器人实时自我检测；机械结构的有限元分析、动力学分析和运动学分析，可以准确预测机器人在管道内部运行的实际情况，找到机器人运动状态的极限情况，防止出现卡死等意外状况；最后基于卡尔曼滤波和模糊逻辑器的多传感器融合检测系统，能有效排除噪声等因素的干扰，准确感知管道环境，并进行建模分析。

{{< figure src="second.jpg" title="" lightbox="true" >}}

通过自行设计硬件设备和软件算法相结合，可以实现机器人在管道内的自主运行；搭载的漏磁检测和激光雷达等传感器，能够实现对管道进行无损检测，检测的准确性高达 99.3%，并且可以节约一半以上的时间。

{{< figure src="3.jpg" title="" lightbox="true" >}}


{{< figure src="featured.jpg" title="" lightbox="true" >}}
