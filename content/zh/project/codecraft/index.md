---
title: 金融风控的资金流水分析
summary: 2020huaweiCodeCraft
tags:
- Data Mining
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

开发金融风控算法，基于给定的资金流水，进行数据挖掘与分析，检测并输出输入资金流水内包含指定约束条件的所有循环转账个数和循环转账路径详情，辅助公安挖掘洗钱组织，帮助银行预防信用卡诈骗。
{{< figure src="9.png" title="" lightbox="true" >}}

算法基于鲲鹏920加速，测试转账金额为32位正整数，转账记录200万条，用时2.74秒，正确率100%。

{{< figure src="result.png" title="" lightbox="true" >}}

算法测试结果荣获江山赛区64强，晋级复赛，遗憾的是因课题组项目验收，未继续参加后续比赛。

{{< figure src="result.jpg" title="" lightbox="true" >}}
