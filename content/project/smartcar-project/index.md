---
title: Double Smart Cars
summary: Double cars chase and overtake on the road.
tags:
- Control system
date: "2017-08-27T00:00:00Z"

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

In this contest, we design two cars to finish the race in as short a time as possible. During special sections, the car behind should overtake the car in front.

To finish the contest, we started learning the MCU of K60, including the output of PWM, communication of UART, and other interface with different sensor, like the camera, ultrasonic, IMU, and so on. Then we designed the circuit board for two cars to integrate various interfaces and modules. After assembling two cars, the camera is used to recognize the different type of race, the PID is used to close up the speed of motors, and the ultrasonic is used to detect the distance between two cars during the running and overtaking.

We got the national 2nd prize in the National Undergraduate Smart Car Contest, which is the most important contest in major of Automation. As the captain, the embedded programing, control algorithm and mechanical adjustment are my contributions.

{{< figure src="zhengshu.jpg" title="" lightbox="true" >}}

{{< figure src="team.png" title="" lightbox="true" >}}

{{< video library="1" src="smartcar.mp4" controls="yes" >}}
