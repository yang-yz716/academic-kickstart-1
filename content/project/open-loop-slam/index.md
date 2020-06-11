---
title: Cloud-based Open loop optimize SLAM
summary: Open loop optimize SLAM based on Cartographer
tags:
- SLAM
date: "2019-01-27T00:00:00Z"

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
We design the mobile robot by myself, including the machine design, motor driver, and all the communication with miniPC.

Based on Cartographer, we focus on how to build map in gallery with sparse features using 2D laser. Apriltag is used as the position-known landmark to build the constraint and add it to global optimization. The accumulated error is adjusted by the extra constraint in sparse feature gallery and the failure of building map is avoided. Websocket is used to achieve the cloud-based mapping, which the sensor data is captured by the mobile robot and calculation is run in the cloud server.

{{< figure src="board.png" title="" lightbox="true" >}}

{{< video library="1" src="slam.mp4" controls="yes" >}}

{{< video library="1" src="open-loop.mp4" controls="yes" >}}
