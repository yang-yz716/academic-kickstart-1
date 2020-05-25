---
title: Synchronous robot
summary: How to run with a slide bar in two cars.
tags:
- Control system
date: "2017-10-27T00:00:00Z"

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

In this project, two cars which hold the end of a pipe run around the same center side-by-side to keep a smooth pipe from slipping. 

The STM32f103 is used to receive the sensor data, calculate the control algorithm and output the PWM signal of motor. We use the camera to detect the black line to track, use the rotary potentiometer to detect the relative position between two cars and use PID algorithm to control one car follow another car. To prevent the pipe slipping out, we design the relative accelerated speed between two cars to let the pipe slide outward during the curve, so the slide inward can in the straightway can be counteracted. The sensor of optoelectronic switch is used to detect the pipe's position of sliding in outside car.

We won the champion in this group of the 5th Shandong Provincial University Robot Competition by runing 41 laps without sliding the pipe in three minutes. The result is twice over the second place.
Our team contains three people. As the captain, the whole design and debug of the code, and the improvement of the machinery.

{{< figure src="syn.png" title="" lightbox="true" >}}

{{< video library="1" src="syn.mp4" controls="yes" >}}
