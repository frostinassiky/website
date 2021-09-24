---
title: Boundary-sensitive Pre-training for Temporal Localization in Videos
publication_types:
  - "1"
authors:
  - Mengmeng Xu
  - Juan-Manuel Perez-Rua
  - Victor Escorcia
  - Brais Martinez
  - Xiatian Zhu
  - Li Zhang
  - Bernard Ghanem
  - Tao Xiang
publication: In *ICCV'21*
abstract: Many video analysis tasks require temporal localization thus detection
  of content changes. However, most existing models developed for these tasks
  are pre-trained on general video action classification tasks. This is because
  large scale annotation of temporal boundaries in untrimmed videos is
  expensive. Therefore no suitable datasets exist for temporal
  boundary-sensitive pre-training. In this paper for the first time, we
  investigate model pre-training for temporal localization by introducing a
  novel boundary-sensitive pretext (BSP) task. Instead of relying on costly
  manual annotations of temporal boundaries, we propose to synthesize temporal
  boundaries in existing video action classification datasets. With the
  synthesized boundaries, BSP can be simply conducted via classifying the
  boundary types. This enables the learning of video representations that are
  much more transferable to downstream temporal localization tasks. Extensive
  experiments show that the proposed BSP is superior and complementary to the
  existing action classification based pre-training counterpart, and achieves
  new state-of-the-art performance on several temporal localization tasks.
draft: false
featured: true
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
summary: >
  Most existing models for temporal localization tasks are pre-trained on video
  classification tasks. The domain gap

  between action recognition and localization can be addressed by a temporal boundary datasets.


  • For the first time, we investigate pre-training for localization by introducing a novel boundary-sensitive pretext task.


  • We propose to synthesize temporal boundaries in existing video classification datasets to help localize action.


  • Extensive experiments show that the proposed BSP is superior and complementary to the existing action classification

  based pre-training counterpart, and achieves new state-of-the-art performance on several temporal localization tasks.
date: 2021-09-24T14:04:51.468Z
---
