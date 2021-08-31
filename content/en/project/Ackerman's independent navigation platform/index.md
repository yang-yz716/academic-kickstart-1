---
title: Wheeled Robot
summary: Ackerman's Independent Navigation Platform
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
Undertook the research and development of low-speed outdoor logistics vehicles based on Ackerman's structure site commissioned by Inspur Company.

{{< figure src="car1.jpg" title="" lightbox="true" >}}

Main responsibilities: development of navigation control system and safety protection system. The operator will debug according to the planned route, complete the environmental scan and build the map. The laser navigation sensor scans the scene during operation, and automatically drives through the map matching, and can be carried out through the GNSS system in the outdoor scene. Global positioning, when driving, if an obstacle is encountered, the robot automatically stops moving, and can resume driving after the obstacle disappears, or choose a detour to avoid obstacles;

{{< figure src="car2.jpg" title="" lightbox="true" >}}

Acceptance criteria: operating in an environment with undulating roads, 2D laser mapping area ≥ 1W square meters, outdoor positioning in open areas ≤ 10 cm, indoor laser positioning accuracy ≤ 3 cm, autonomous planning of paths, real-time obstacle avoidance operation for dynamic objects , The vehicle running speed ≥ 1 m/s.

{{< video library="1" src="Trim.mp4" controls="no" >}}
