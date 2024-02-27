---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Exploiting Subgraph Similarities for Efficient Auto-tuning of Tensor Programs
subtitle: ''
summary: ''
authors:
- Mingzhen Li
- Hailong Yang
- Shanjun Zhang
- Fengwei Yu
- Ruihao Gong
- Yi Liu
- Zhongzhi Luan
- Depei Qian
tags:
- Auto-tuning
- Performance Optimization
- Subgraph Similarity
- Tensor Compiler
categories: []
date: '2023-01-01'
lastmod: 2024-02-27T22:49:53+08:00
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
publishDate: '2024-02-27T14:49:53.045075Z'
publication_types:
- '1'
abstract: The requirement for deploying deep learning (DL) models efficiently has
  boosted the research of DL compilers. Especially, the difficulty of generating optimized
  tensor programs has driven DL compilers to commonly adopt the auto-tuning approaches.
  Consequently, there are increasing demands to improve the effectiveness of auto-tuning
  in terms of both search efficiency and search quality. However, existing auto-tuning
  approaches commonly treat subgraphs individually and overlook the similarities among
  them, and thus fail to generate better tensor programs under limited time budget.
  To address the above drawbacks, we propose FamilySeer, an auto-tuning framework
  that can generate better tensor programs by exploiting the subgraph similarities.
  Specifically, FamilySeer organizes similar subgraphs into subgraph families, where
  the cost models are built at family basis with improved accuracy for estimating
  high potential program candidates. To further leverage the similarity, FamilySeer
  uses the accurate cost model per family to reduce the number of program candidates
  for costly hardware measurements without degrading search quality. The experiment
  results on various DL models demonstrate that FamilySeer can achieve better search
  efficiency/quality on both CPU and GPU platforms compared to the state-of-the-art
  auto-tuning framework.
publication: '*Proceedings of the 52nd International Conference on Parallel Processing*'
doi: 10.1145/3605573.3605596
links:
- name: URL
  url: https://doi.org/10.1145/3605573.3605596
---
