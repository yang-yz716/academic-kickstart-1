---
title: The design of control board
summary: Embedded board with control, hardware and shell 
tags:
- Control system
date: "2019-03-27T00:00:00Z"

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

We designed the embedded control board hardware and shell which are shown as follows. More than ten boards are controlled simultaneously and each board communicates with server by CAN. The control board is used to read the wheel encoder, detect the environment humidity and pH value, and control strong electricity (220 AC) by weak current (5V DC).

{{< figure src="cascade.jpg" title="" lightbox="true" >}}
