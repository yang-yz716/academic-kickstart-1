---
title: Target-driven Visual Navigation
summary: The priors represented by scene graph are incorporated in deep reinforcement learning model using R-GCN on Habitat platform.
tags:
- RL
date: "2020-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Zhu et al.'s work is the first one that addresses the problem of target-driven visual navigation, his work is shown as follows:
{{< figure src="1.png" title="" lightbox="true" >}}

In ICLR 2019, the work that using scene prior to achieve visual semantic navigation:
{{< figure src="2.png" title="" lightbox="true" >}}

In arxiv 2020, the features of scene graph are more common used to represent the 3D spatial information:
{{< figure src="3.png" title="" lightbox="true" >}}

All the above works use AI2-THOR framework, which is limited to the single room, such as “kitchen” or “bathroom”, but the real scene is always the multi-room scene. Habitat is a good platform to provide the multi-room scene to achieve the target-driven semantic navigation.

According to the prior work, I think the task of ObjectNav in multi-room scene is not trivial if we don’t make good use of prior knowledge, and the 3D scene graphs are good priors! Now I focus on how to incorporate the prior knowledge in deep reinforcement learning model using R-GCN on Habitat platform and design a framework:
{{< figure src="framework.png" title="The framework of target-driven semantic navigation." lightbox="true" >}}
I think it’s very interesting research for the mobile robot and by this way the robot can really understand the world better.

Now I have build my own Objectnav datasets using Gibson. The detail of the Objectnav datasets are shown in "https://github.com/ybgdgh/Habitat-Objectnav-Task-Datadet-Geneartion".

{{< video library="1" src="trajectory.mp4" controls="yes" >}}
