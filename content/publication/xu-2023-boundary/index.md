---
title: Boundary-denoising for video activity localization
authors:
- Mengmeng Xu
- Mattia Soldan
- Jialin Gao
- Shuming Liu
- Juan-Manuel Pérez-Rúa
- Bernard Ghanem
date: '2023-01-01'
publishDate: '2024-02-29T22:35:36.183665Z'
publication_types:
- "1"
publication: 'ICLR 2024'
featured: true
abstract: Video activity localization aims at understanding the semantic content in long, untrimmed videos and retrieving actions of interest. The retrieved action with its start and end locations can be used for highlight generation, temporal action detection, etc. Unfortunately, learning the exact boundary location of activities is highly challenging because temporal activities are continuous in time, and there are often no clear-cut transitions between actions. Moreover, the definition of the start and end of events is subjective, which may confuse the model. To alleviate the boundary ambiguity, we propose to study the video activity localization problem from a denoising perspective. Specifically, we propose an encoder-decoder model named DenosieLoc. During training, a set of action spans is randomly generated from the ground truth with a controlled noise scale. Then, we attempt to reverse this process by boundary denoising, allowing the localizer to predict activities with precise boundaries and resulting in faster convergence speed. Experiments show that DenosieLoc advances several video activity understanding tasks. For example, we observe a gain of +12.36% average mAP on the QV-Highlights dataset. Moreover, DenosieLoc achieves state-of-the-art performance on the MAD dataset but with much fewer predictions than others.
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
