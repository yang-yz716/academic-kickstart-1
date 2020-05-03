---
title: 3D structured semantic scene graph
summary: The semantic environment model of 3D structured scene graph for the implementation of robot task
tags:
- SLAM
date: "2020-03-27T00:00:00Z"

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

Aliquam in turpis accumsan, malesuada nibh ut, hendrerit justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque sed erat nec justo posuere suscipit. Donec ut efficitur arcu, in malesuada neque. Nunc dignissim nisl massa, id vulputate nunc pretium nec. Quisque eget urna in risus suscipit ultricies. Pellentesque odio odio, tincidunt in eleifend sed, posuere a diam. Nam gravida nisl convallis semper elementum. Morbi vitae felis faucibus, vulputate orci placerat, aliquet nisi. Aliquam erat volutpat. Maecenas sagittis pulvinar purus, sed porta quam laoreet at.

We used AOG to construct the prior knowledge.

{{< figure src="AOG.jpg" title="The AOG structure." lightbox="true" >}}

{{< figure src="infer.jpg" title="The infer from perception." lightbox="true" >}}

{{< figure src="result_graph.jpg" title="The result of the parse graph from different methods." lightbox="true" >}}

{{< figure src="result_table.jpg" title="The result of the accuracy from different methods." lightbox="true" >}}

We use laser to provide the location information and use scene graph to finish the navigation.

{{< figure src="demo.jpg" title="The demo in webots to achieve the task of semantic navigation." lightbox="true" >}}

{{< video library="1" src="Iros.mp4" controls="yes" >}}
