---
title: 轮式机器人
summary: 阿克曼自主导航平台
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
受浪潮公司委托，合作研发基于阿克曼结构的低速户外物流车。

{{< figure src="car1.jpg" title="" lightbox="true" >}}

开发导航控制系统和安全防护系统，由操作人员按照规划路线调试，完成环境扫描并建立地图，运行时激光导航传感器扫描现场，通过匹配地图，自动行驶，可在室外场景通过GNSS系统进行全局定位，行驶时，如遇障碍，机器人自动停止运动，障碍消失后可恢复行驶，或选择绕行方式避障。 

{{< figure src="car2.jpg" title="" lightbox="true" >}}

验收标准：在道路有起伏的环境中运行，二维激光建图面积≥1W平方米，室外空旷处定位≤10厘米，室内激光定位精度≤3厘米，自主规划路径，对动态物体实时避障运行，车辆运行时速≥1米/秒。

{{< video src="Trim.mp4" controls="yes" >}}
