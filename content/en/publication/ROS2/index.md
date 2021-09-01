---
title: "A Distributed Cloud Navigation System and Navigation Method Based On ROS2"
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

abstract: The present disclosure provides a distributed cloud navigation system and navigation method based on ROS2. Among them, the system includes the bottom layer, which includes at least one robot. The robots are equipped with sensor modules. The sensor modules are used to collect the robot's environmental data and its own motion state data. Among them, the robot and its interactive devices respectively serve as nodes to form a ROS network; The global data space, as a network layer, is used to realize the mutual communication between the robot and the cloud server, and to receive topic publishing or topic subscription related data sent by each node in the ROS network; the cloud server, which is configured to receive the robot uploads Environmental data and its own motion state data, calculate the control information of the robot and locate and plan the path of the robot, so that the robot can move to the designated position; the management layer is configured to communicate with each node in the ROS network. To monitor the running status of the distributed cloud navigation system. 

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

{{< figure src="1.jpg" title="The framework of our approach." lightbox="true" >}}

