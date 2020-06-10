---
title: Target-driven Visual Navigation
summary: The visual and prior features are concatenated to the deep reinforcement learning model to achieve the semantic target navigation.
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

This paper presented a bottom-up framework of structured 3D scene graph generation from RGB-D image and scene priors. The proposed framework contains an improved grammar model, which is used to learn from scene dataset and describe the scene priors. The visual perception is used to capture the objects, relations and attributes from 3D scene, and the inference was adopted to obtain the optimal parse graph from scene priors. We implement our framework in a real indoor scene to demonstrate its accuracy in representing the semantic information, and the applicability of the high-level human-robot interaction navigation tasks is also verified in multi-room scene using human command. For further research, the dynamic semantic segmentation system can be used to improve the visual perception. The structure of the S-AOG is easy to expand, with the hierarchy of the S-AOG addition can help robots to execute more complex semantic tasks, such as autonomous exploration in unseen scene and the improvement of the visual perception using context grammar.

{{< figure src="AOG.jpg" title="The AOG structure." lightbox="true" >}}

{{< figure src="infer.jpg" title="The infer from perception." lightbox="true" >}}

{{< figure src="result_graph.jpg" title="The result of the parse graph from different methods." lightbox="true" >}}

{{< figure src="result_table.jpg" title="The result of the accuracy from different methods." lightbox="true" >}}

We use laser to provide the location information and use scene graph to achieve the target-driven navigation.

{{< figure src="demo.jpg" title="The demo in webots to achieve the task of semantic navigation." lightbox="true" >}}

{{< video library="1" src="Iros.mp4" controls="yes" >}}
