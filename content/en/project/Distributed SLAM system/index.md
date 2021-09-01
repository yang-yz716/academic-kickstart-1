---
title: Distributed SLAM
summary: Service-Robot Cloud Service Technology
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

The implementation tasks of the SLAM system based on ROS2 mainly include the construction of the bottom two-wheel differential experimental platform and the debugging of the system program framework. The experimental platform can be controlled by the handle to complete positioning and mapping in an unknown indoor environment, and can adapt to Damage to the network environment to ensure data safety and reliability.

{{< figure src="AAAA.jpg" title="" lightbox="true" >}}

A distributed standard framework based on ROS2 is mainly composed of four parts: cloud server, middle management, global data space, and underlying robot. The system architecture is simple in level and has good practicability. All robots developed based on ROS2 and computing devices that support the ROS2 system can be connected to the system through a unified interface and according to the structure level.

{{< figure src="STRUCTURE.jpg" title="" lightbox="true" >}}

The two-wheel differential motion platform is equipped with a 16.8V lithium battery for power supply. The 12V DC geared motor, the communication circuit and the 3.3V operating voltage STM32 main control chip are powered by a step-by-step voltage regulator circuit. The bottom layer is equipped with three different forms of communication modes such as serial communication and RS232 communication to meet the communication needs in different environments. The OLED seven-pin display can display the value of program parameters in real time, which is convenient for later function debugging.

{{< figure src="1AS.jpg" title="" lightbox="true" >}}


The ROS1 executable program is updated and transplanted based on the ROS2 code structure, and the system software node distribution diagram is shown in the figure.

{{< figure src="34.jpg" title="" lightbox="true" >}}

{{< figure src="33.jpg" title="" lightbox="true" >}}

{{< figure src="32.jpg" title="" lightbox="true" >}}

{{< figure src="2222.jpg" title="" lightbox="true" >}}

The real shot and structure layout of the scene are shown in the figure.


{{< figure src="MAPPING.jpg" title="" lightbox="true" >}}

The distributed SLAM system based on ROS2 can efficiently complete the tasks of positioning and map construction, and the mapping effect is basically the same as the widely used ROS1 system framework. ROS2 uses the DDS node discovery mechanism to replace the ROS1 node manager. There is no need to start the layout operation of ROS_Master. In the application of multi-robot system, many complicated start-up steps will be omitted, which greatly improves the work efficiency of the system and the user experience.

{{< video src="N1.mp4" controls="yes" >}}

{{< video src="N2.mp4" controls="yes" >}}