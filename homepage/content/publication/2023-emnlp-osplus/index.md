---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Outlier Suppression+: Accurate quantization of large language models by equivalent
  and effective shifting and scaling'
subtitle: ''
summary: ''
authors:
- Xiuying Wei
- Yunchen Zhang
- Yuhang Li
- Xiangguo Zhang
- Ruihao Gong
- Jinyang Guo
- Xianglong Liu
tags: []
categories: []
date: '2023-12-01'
lastmod: 2024-02-27T22:50:36+08:00
featured: true
draft: false

url_pdf: 'https://aclanthology.org/2023.emnlp-main.102/'
url_code: 'https://github.com/ModelTC/Outlier_Suppression_Plus'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
publishDate: '2024-02-27T14:50:36.439363Z'
publication_types:
- '1'
abstract: Post-training quantization (PTQ) of transformer language models faces significant
  challenges due to the existence of detrimental outliers in activations. We observe
  that these outliers are concentrated in specific channels and are asymmetric across
  channels. To address this issue, we propose the Outlier Suppression+ (OS+) framework,
  which contains the channel-wise shifting for asymmetry and channel-wise scaling
  for concentration. We show that these operations can be seamlessly migrated into
  subsequent modules while maintaining equivalence. Second, we propose a fast and
  stable scheme to calculate effective shifting and scaling values. The channel-wise
  shifting aligns the center of each channel for removal of outlier asymmetry. The
  channel-wise scaling quantitatively evaluates changes brought by migration and quantization
  for better quantization burden balance. We validate our OS+ under both standard
  and fine-grained quantization settings with models including BERT, OPT, BLOOM, BLOOMZ,
  and LLaMA. Comprehensive results across various tasks demonstrate the superiority
  of our approach. Especially, with standard quantization, OS+ can achieve near-floating-point
  performance on both small models and large language models on 8-bit and 6-bit. Besides,
  we establish a new state-of-the-art for 4-bit BERT with 15.5% improvement. Our code
  is available at r̆lhttps://github.com/ModelTC/Outlier_Suppression_Plus.
publication: '*Proceedings of the 2023 Conference on Empirical Methods in Natural
  Language Processing*'
doi: 10.18653/v1/2023.emnlp-main.102
links:
- name: URL
  url: https://aclanthology.org/2023.emnlp-main.102
---
