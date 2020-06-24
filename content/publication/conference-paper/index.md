---
title: "A Bottom-up Framework for Construction of Structured Semantic 3D Scene Graph"
authors:
- Bangguo Yu
- Chongyu Chen
- Fengyu Zhou*
- Fang Wan
- Wenmi Zhuang
- Yang Zhao
date: "2020-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2020 IEEE/RSJ International Conference on Intelligent Robots and Systems*
publication_short: In *IROS*

abstract: Abstract—For high-level human-robot interaction tasks, 3D scene understanding is important and non-trivial for autonomous robots. However, parsing and utilizing effective environment information of the 3D scene is not trivial due to the complexity of the 3D environment and the limited ability for reasoning about our visual world. Although there have been great efforts on semantic detection and scene analysis, the existing solutions for parsing and representation of the 3D scene still fail to preserve accurate semantic information and equip sufficient applicability. This study proposes a bottomup construction framework for structured 3D scene graph generation, which efficiently describes the objects, relations and attributes of the 3D indoor environment with structured representation. In the proposed method, we adopt visual perception to capture the semantic information and inference from scene priors to calculate the optimal parse graph. Afterwards, an improved probabilistic grammar model is used to represent the scene priors. Experiment results demonstrate that the proposed framework significantly outperforms existing methods in terms of accuracy, and a demonstration is provided to verify the applicability in applying to high-level human-robot interaction tasks.

# Summary. An optional shortened abstract.
summary: submitted

tags:
- SLAM
featured: true

links:
- name: pdf
  url: = "files/cv.pdf"
# url_pdf: url = "files/cv.pdf"
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '3D scene graph'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{< figure src="AOG.jpg" title="The AOG structure." lightbox="true" >}}

{{< figure src="infer.jpg" title="The infer from perception." lightbox="true" >}}

{{< figure src="result_graph.jpg" title="The result of the parse graph from different methods." lightbox="true" >}}

{{< figure src="result_table.jpg" title="The result of the accuracy from different methods." lightbox="true" >}}

We use laser to provide the location information and use scene graph to achieve the target-driven navigation.

{{< figure src="demo.jpg" title="The demo in webots to achieve the task of semantic navigation." lightbox="true" >}}

{{< video library="1" src="Iros.mp4" controls="yes" >}}
