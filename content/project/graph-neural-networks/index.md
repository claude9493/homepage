---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Graph Neural Networks"
summary: "Graph neural networks."
authors: []
tags: [Deep Learning, Graph Neural Networks]
categories: []
date: 2021-09-05T23:47:30+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
> I am currently learning some basic concepts related to Graph Neural Networks (GNN) and representation learning.

## Node2Vec: simulations of biased random walks

I use this open-source [node2vec](https://github.com/eliorc/node2vec) implementation to simulate biased random walks in the node2vec algorithm. Following two videos illustrate the in-out parameter $q$'s role played in random walks with fixed return parameter $p$, i.e. a "ratio" of BFS vs. DFS.

- High in-out parameter $q$, Micro-view of neighbourhood, BFS
{{< video src="biased-random-walk-BFS.mp4" controls="yes" >}}

- Low in-out parameter $q$, Macro-view of neighbourhood, DFS
{{< video src="biased-random-walk-DFS.mp4" controls="yes" >}}
