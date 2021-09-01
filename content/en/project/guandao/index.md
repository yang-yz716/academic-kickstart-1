---
title: Pipeline Robots
summary: Service-Robot Cloud Service Technology
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

The main innovations of the robot are: firstly, an independently driven three-legged symmetrical design is designed to improve the robot's motion while adapting to various pipe diameters; secondly, a multi-scene motion guarantee system is designed to guarantee the stable operation of the robot; Last but not least, algorithms such as Kalman filter and fuzzy logger improve the accuracy of environmental detection.

{{< figure src="first.jpg" title="" lightbox="true" >}}

The robot adopts a three-legged symmetrical crawler type independent drive design, which can adapt to the change of large pipeline diameter. High-power motor drive board and power management system guarantee the safe and stable operation of the robot in the pipeline. Fuzzy algorithm and energy modeling that can help the robot to control and improve the range precisely and flexibly. Feedback circuits such as voltage loop, current loop and pressure loop to realize real-time self-detection of the robot. Finite element analysis, dynamics analysis and kinematics analysis of the mechanical structure can accurately predict the actual situation of the robot running inside the pipeline, find the limit situation of the robot's motion state and prevent unexpected conditions such as jamming. Finally, the multi-sensor fusion detection system based on Kalman filter and fuzzy logger can effectively exclude the interference of noise and other factors, accurately perceive the pipeline environment, and perform modeling analysis.

{{< figure src="second.jpg" title="" lightbox="true" >}}

In response to the current problems of pipeline robots, the team designed a non-destructive inspection robot for large pipelines. Through the combination of self-designed hardware equipment and software algorithms, the robot can operate autonomously in the pipeline; equipped with magnetic flux leakage detection Sensors such as Lidar and Lidar, combined with Kalman filtering and multi-sensor fusion technology, can perform non-calculated detection of pipelines. The detection accuracy is as high as 99.3%, and more than half of the time can be saved.

{{< figure src="3.jpg" title="" lightbox="true" >}}


{{< figure src="featured.jpg" title="" lightbox="true" >}}
