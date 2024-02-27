---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Generating Transferable Adversarial Examples against Vision Transformers
subtitle: ''
summary: ''
authors:
- Yuxuan Wang
- Jiakai Wang
- Zixin Yin
- Ruihao Gong
- Jingyi Wang
- Aishan Liu
- Xianglong Liu
tags:
- vision transformer
- transferability
- adversarial attacks
categories: []
date: '2022-01-01'
lastmod: 2024-02-27T22:19:39+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-02-27T14:19:39.332560Z'
publication_types:
- '1'
abstract: Vision transformers (ViTs) are prevailing among several visual recognition
  tasks, therefore drawing intensive interest in generating adversarial examples against
  them. Different from CNNs, ViTs enjoy unique architectures, e.g., self-attention
  and image-embedding, which are commonly-shared features among various types of transformer-based
  models. However, existing adversarial methods suffer from weak transferable attacking
  ability due to the overlook of these architectural features. To address the problem,
  we propose an Architecture-oriented Transferable Attacking (ATA) framework to generate
  transferable adversarial examples by activating the uncertain attention and perturbing
  the sensitive embedding.Specifically, we first locate the patch-wise attentional
  regions that mostly affect model perception, therefore intensively activating the
  uncertainty of the attention mechanism and confusing the model decisions in turn.Furthermore,
  we search the pixel-wise attacking positions that are more likely to derange the
  embedded tokens using sensitive embedding perturbation, which could serve as a strong
  transferable attacking pattern.By jointly confusing the unique yet widely-used architectural
  features among transformer-based models, we can activate strong attacking transferability
  among diverse ViTs. Extensive experiments on large-scale dataset ImageNet using
  various popular transformers demonstrate that our ATA outperforms other baselines
  by large margins (at least +15% Attack Success Rate). Our code is available at https://github.com/nlsde-safety-team/ATA
publication: '*Proceedings of the 30th ACM International Conference on Multimedia*'
doi: 10.1145/3503161.3547989
links:
- name: URL
  url: https://doi.org/10.1145/3503161.3547989
---
