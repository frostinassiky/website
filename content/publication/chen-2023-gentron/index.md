---
title: 'GenTron: Delving Deep into Diffusion Transformers for Image and Video Generation'
authors:
- Shoufa Chen *
- Mengmeng Xu *
- Jiawei Ren
- Yuren Cong
- Sen He
- Yanping Xie
- Animesh Sinha
- Ping Luo
- Tao Xiang
- Juan-Manuel Perez-Rua
date: '2023-01-01'
publishDate: '2024-02-29T22:35:36.171167Z'
publication_types:
- "1"
publication: 'CVPR 2024'
featured: true
abstract: In this study, we explore Transformer-based diffusion models for image and video generation. Despite the dominance of Transformer architectures in various fields due to their flexibility and scalability, the visual generative domain primarily utilizes CNN-based U-Net architectures, particularly in diffusion-based models. We introduce GenTron, a family of Generative models employing Transformer-based diffusion, to address this gap. Our initial step was to adapt Diffusion Transformers (DiTs) from class to text conditioning, a process involving thorough empirical exploration of the conditioning mechanism. We then scale GenTron from approximately 900M to over 3B parameters, observing significant improvements in visual quality. Furthermore, we extend GenTron to text-to-video generation, incorporating novel motion-free guidance to enhance video quality. In human evaluations against SDXL, GenTron achieves a 51.1% win rate in visual quality (with a 19.8% draw rate), and a 42.3% win rate in text alignment (with a 42.9% draw rate). GenTron also excels in the T2I-CompBench, underscoring its strengths in compositional generation. We believe this work will provide meaningful insights and serve as a valuable reference for future research.
image:
  caption: 'GenTron: Transformer based diffusion model for high-quality text-to-image/video generation.'
  focal_point: ""
  placement: 2
  preview_only: false
---
