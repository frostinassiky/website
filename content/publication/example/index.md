---
abstract: "Temporal action detection is a fundamental yet challeng\x02ing task
  in video understanding. Video context is a critical cue to effectively detect
  actions, but current works mainly focus on temporal context, while neglecting
  semantic con\x02text as well as other important context properties. In this
  work, we propose a graph convolutional network (GCN) model to adaptively
  incorporate multi-level semantic con\x02text into video features and cast
  temporal action detection as a sub-graph localization problem. Specifically,
  we for\x02mulate video snippets as graph nodes, snippet-snippet
  cor\x02relations as edges, and actions associated with context as

  target sub-graphs. With graph convolution as the basic operation, we design
  a GCN block called GCNeXt, which learns the features of each node by
  aggregating its context and dynamically updates the edges in the graph. To
  local\x02ize each sub-graph, we also design an SGAlign layer to em\x02bed each
  sub-graph into the Euclidean space. Extensive ex\x02periments show that G-TAD
  is capable of finding effective

  video context without extra supervision and achieves state\x02of-the-art
  performance on two detection benchmarks. On ActivityNet-1.3, it obtains an
  average mAP of 34.09%; on THUMOS14, it reaches 51.6% at IoU@0.5 when combined
  with a proposal processing method. "
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Mengmeng Xu
  - Chen Zhao
  - David S. Rojas
  - Ali Thabet
  - Bernard Ghanem
author_notes: []
publication: In *CVPR20*
summary: >
  Recent studies show that context can be used as a clue to help understanding
  action before or after the snippet. Thus,

  we formulated action localization task to a sub-graph detection problem, solved by graph convolutional network.


  • A multi-graph convolutional layer is designed to progressively represent the video snippet by its adaptive semantics.


  • The method achieves SOTA performance on two large-scale video benchmarks for human activity localization.
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: "G-TAD: Sub-Graph Localization for Temporal Action Detection"
doi: ""
featured: true
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.png
date: 2013-07-01T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
