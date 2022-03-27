---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Binary neural networks: A survey'
subtitle: ''
summary: ''
authors:
- Haotong Qin
- Ruihao Gong
- Xianglong Liu
- Xiao Bai
- Jingkuan Song
- Nicu Sebe
tags:
- Binary neural network
- Deep learning
- Model compression
- Network quantization
- Model acceleration
categories: []
date: '2020-01-01'
lastmod: 2022-03-27T15:27:48+08:00
featured: true
draft: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
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
publishDate: '2022-03-27T07:29:05.018687Z'
publication_types:
- '2'
abstract: The binary neural network, largely saving the storage and computation, serves
  as a promising technique for deploying deep models on resource-limited devices.
  However, the binarization inevitably causes severe information loss, and even worse,
  its discontinuity brings difficulty to the optimization of the deep network. To
  address these issues, a variety of algorithms have been proposed, and achieved satisfying
  progress in recent years. In this paper, we present a comprehensive survey of these
  algorithms, mainly categorized into the native solutions directly conducting binarization,
  and the optimized ones using techniques like minimizing the quantization error,
  improving the network loss function, and reducing the gradient error. We also investigate
  other practical aspects of binary neural networks such as the hardware-friendly
  design and the training tricks. Then, we give the evaluation and discussions on
  different tasks, including image classification, object detection and semantic segmentation.
  Finally, the challenges that may be faced in future research are prospected.
publication: '*Pattern Recognition*'
doi: https://doi.org/10.1016/j.patcog.2020.107281
links:
- name: URL
  url: http://www.sciencedirect.com/science/article/pii/S0031320320300856
---
