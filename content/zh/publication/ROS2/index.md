---
title: "一种基于ROS2的分布式云导航系统及导航方法"
authors:
- Fengyu Zhou
- Zhiyong Yang
- Fang Wan
- Junjian Bian
date: "2020-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
publication: State Intellectual Property Office of the P.R.C
publication_short: In *CNIPA*

abstract: 本公开提供了基于ROS2的分布式云导航系统及导航方法。其中,该系统包括底层,其包括至少一个机器人,机器人上均搭载有传感器模块,传感器模块用于采集机器人的环境数据及自身运动状态数据；其中,机器人与其交互设备分别作为节点进而构成ROS网络；全局数据空间,其作为网络层,用于实现机器人与云端服务器之间相互通信,且接收ROS网络中各个节点中发出的话题发布或话题订阅相关数据；云端服务器,其被配置为接收机器人上传的环境数据及自身运动状态数据,计算出机器人的控制信息并对对机器人进行定位及路径规划,使该机器人移动到达指定的位置；管理层,其被配置为与ROS网络中各个节点相互通信,用来监控分布式云导航系统的运行状态

# Summary. An optional shortened abstract.
summary: CN201910808415.4
tags:
- Robotics Navigation
featured: true

# links:
# - name: Custom Link
#   url: = "files/cv.pdf"
# url_pdf: url = "files/cv.pdf"
#url_code: 'https://github.com/ybgdgh/Visual-Target-Navigation'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
#url_video: 'https://youtu.be/IhUz0O11aBo'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'target navigation'
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- target navigation

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{< figure src="1.jpg" title="系统架构" lightbox="true" >}}

