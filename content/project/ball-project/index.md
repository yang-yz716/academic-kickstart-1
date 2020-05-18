---
title: Ball and Plate Control System
summary: National Undergraduate Electronocs Design Contest
tags:
- Control system
date: "2017-08-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Our team designed a Ball and Plate control system with rgb camera. We used camera to detect the color, position and velocity of the ball, and used the PID algorithm to set the velocity and position close loop to achieve the control performance of ball's movement. The ball running around the center and tracking other ball are shown as follows.

{{< figure src="machine.jpg" title="" lightbox="true" >}}

{{< video library="1" src="ball.mp4" controls="yes" >}}
