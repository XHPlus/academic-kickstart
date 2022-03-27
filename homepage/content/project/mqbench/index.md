---
title: MQBench
summary: MQBench is an open-source model quantization toolkit based on PyTorch fx, which provides **SOTA Algorithms** and **Powerful Toolkits**.
tags:
- Deep Learning
date: "2021-07-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
# external_link: "http://mqbench.tech/"

image:
  caption: MQBench
  focal_point: Smart

url_code: "https://github.com/ModelTC/MQBench"
url_pdf: "https://openreview.net/pdf?id=TUplOmF8DsM"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

MQBench is an open-source model quantization toolkit based on PyTorch fx.

The envision of MQBench is to provide:

- SOTA Algorithms. With MQBench, the hardware vendors and researchers can benefit from the latest research progress in academia.
- Powerful Toolkits. With the toolkit, quantization node can be inserted to the original PyTorch module automatically with respect to the specific hardware. After training, the quantized model can be smoothly converted to the format that can inference on the real device.

The documentation can be seen at [Documentation](https://mqbench.readthedocs.io/en/latest/?badge=latest) and the website is at [Link](http://mqbench.tech/).
