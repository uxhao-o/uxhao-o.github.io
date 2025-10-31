---
title: "G2ViT: Graph neural network-guided vision transformer enhanced network for retinal vessel and coronary angiograph segmentation"
authors:
- admin
- Yun Wu
author_notes:
#- "First author"
#- "Corresponding author"
date: "2024-08-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Neural Networks*, 176, 106356"
publication_short: ""

abstract: Blood vessel segmentation is a crucial stage in extracting morphological characteristics of vessels for the clinical diagnosis of fundus and coronary artery disease. However, traditional convolutional neural networks (CNNs) are confined to learning local vessel features, making it challenging to capture the graph structural information and fail to perceive the global context of vessels. Therefore, we propose a novel graph neural network-guided vision transformer enhanced network (G2ViT) for vessel segmentation. G2ViT skillfully orchestrates the Convolutional Neural Network, Graph Neural Network, and Vision Transformer to enhance comprehension of the entire graphical structure of blood vessels. To achieve deeper insights into the global graph structure and higher-level global context cognizance, we investigate a graph neural network-guided vision transformer module. This module constructs graph-structured representation in an unprecedented manner using the high-level features extracted by CNNs for graph reasoning. To increase the receptive field while ensuring minimal loss of edge information, G2ViT introduces a multi-scale edge feature attention module (MEFA), leveraging dilated convolutions with different dilation rates and the Sobel edge detection algorithm to obtain multi-scale edge information of vessels. To avoid critical information loss during upsampling and downsampling, we design a multi-level feature fusion module (MLF2) to fuse complementary information between coarse and fine features. Experiments on retinal vessel datasets (DRIVE, STARE, CHASE_DB1, and HRF) and coronary angiography datasets (DCA1 and CHUAC) indicate that the G2ViT excels in robustness, generality, and applicability. Furthermore, it has acceptable inference time and computational complexity and presents a new solution for blood vessel segmentation.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Medical Image Analysis
featured: true

#hugoblox:
#  ids:
#    arxiv: 1512.04133v1

links:
#  - type: pdf
#    url: http://arxiv.org/pdf/1512.04133v1
#  - type: code
#    url: https://github.com/HugoBlox/hugo-blox-builder
#  - type: dataset
#    url: ""
#  - type: poster
#    url: ""
#  - type: project
#    url: ""
#  - type: slides
#    url: https://www.slideshare.net/
  - type: source
    url: "https://doi.org/10.1016/j.neunet.2024.106356"
#  - type: video
#    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'G2ViT Model Structure Diagram'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

> [!NOTE]
> Click the *Cite* button above to cite this paper.

```bash
@article{xu2024g2vit,
  title={G2ViT: Graph neural network-guided vision transformer enhanced network for retinal vessel and coronary angiograph segmentation},
  author={Xu, Hao and Wu, Yun},
  journal={Neural Networks},
  volume={176},
  pages={106356},
  year={2024},
  publisher={Elsevier}
}
```