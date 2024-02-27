---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Rectify representation bias in vision-language models for long-tailed recognition
subtitle: ''
summary: ''
authors:
- Bo Li
- Yongqiang Yao
- Jingru Tan
- Ruihao Gong
- Jianwei Lu
- Ye Luo
tags:
- Long-tailed recognition
- Vision-language model
- Representation bias
categories: []
date: '2024-01-01'
lastmod: 2024-02-27T22:49:59+08:00
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
publishDate: '2024-02-27T14:49:59.256625Z'
publication_types:
- '2'
abstract: Natural data typically exhibits a long-tailed distribution, presenting great
  challenges for recognition tasks. Due to the extreme scarcity of training instances,
  tail classes often show inferior performance. In this paper, we investigate the
  problem within the trendy visual-language (VL) framework and find that the performance
  bottleneck mainly arises from the recognition confusion between tail classes and
  their highly correlated head classes. Building upon this observation, unlike previous
  research primarily emphasizing class frequency in addressing long-tailed issues,
  we take a novel perspective by incorporating a crucial additional factor namely
  class correlation. Specifically, we model the representation learning procedure
  for each sample as two parts, i.e., a special part that learns the unique properties
  of its own class and a common part that learns shared characteristics among classes.
  By analysis, we discover that the learning process of common representation is easily
  biased toward head classes. Because of the bias, the network may lean towards the
  biased common representation as classification criteria, rather than prioritizing
  the crucial information encapsulated within the specific representation, ultimately
  leading to recognition confusion. To solve the problem, based on the VL framework,
  we introduce the rectification contrastive term (ReCT) to rectify the representation
  bias, according to semantic hints and training status. Extensive experiments on
  three widely-used long-tailed datasets demonstrate the effectiveness of ReCT. On
  iNaturalist2018, it achieves an overall accuracy of 75.4%, surpassing the baseline
  by 3.6 points in a ResNet-50 visual backbone.
publication: '*Neural Networks*'
doi: https://doi.org/10.1016/j.neunet.2024.106134
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0893608024000509
---
