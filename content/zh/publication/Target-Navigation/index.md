---
title: "Visual Target Navigation using 3D Scene Priors"
authors:
- Bangguo Yu
- Fengyu Zhou*
- Ke Chen
- Zhiyong Yang
date: "2020-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Submitted In *2021 IEEE International Conference on Robotics and Automation*
publication_short: In *ICRA2021*

abstract: Recently, visual target navigation is important and non-trivial for autonomous robots because it closely relates to the ability of cognitive reasoning. Classical methods and learning based methods are fundamental components of robot navigation which have been studied for a long time. However, the representation of the scene memory and priors, and the generalization of method in unseen scene are the core challenges due to the complexity and indeterminacy of the indoor scene. Here, we proposed a framework for visual target navigation that efficiently fuses the SLAM and deep reinforcement learning method with explicit 3D scene priors. In the proposed method, we adopt SLAM to build a semantic map as scene memory and learn navigation policy based on the real-time map and explicit scene priors to make the optimal decision. Afterward, the 3D scene priors are generated from Visual Genome dataset and incorporated with the framework using R-GCN. The explicit scene memory and priors can provide more intuitional features for visual target navigation tasks than the implicit representation learning from networks. Experiment results demonstrate that the proposed framework significantly outperforms existing methods in the target navigation task in the unseen scene. We also compared our method with the human subjective decision in visual target navigation.

# Summary. An optional shortened abstract.
summary: (Submitted)The 2021 International Conference on Robotics and Automation (ICRA 2021)
tags:
- Reinforcement Learning
featured: true

# links:
# - name: Custom Link
#   url: = "files/cv.pdf"
# url_pdf: url = "files/cv.pdf"
url_code: 'https://github.com/ybgdgh/Visual-Target-Navigation'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
url_video: 'https://youtu.be/IhUz0O11aBo'

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

{{< figure src="framework.jpg" title="The framework of our approach." lightbox="true" >}}

{{< figure src="R-GCN.jpg" title="The process of the 3D scene priors encoding with R-GCN method." lightbox="true" >}}

{{< figure src="experiment.jpg" title="Viausl target navigation experiment in Habitat simulator to find a couch in different timesteps." lightbox="true" >}}

{{< figure src="results.jpg" title="" lightbox="true" >}}

{{< video library="1" src="Target Navigation.mp4" controls="yes" >}}
