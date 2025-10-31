---
title: "Convolutional state space model with multi-window cross-scan to advance the automated diagnosis of skeletal fluorosis"
authors:
- admin
- Yun Wu
- Rui Xie
- Jun Xu
- Junpeng Wu
- Rongpin Wang
- Youliang Tian
author_notes:
- "First author"
- "Corresponding author"
date: "2025-05-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Biomedical Signal Processing and Control* 103 (2025): 107439"
publication_short: ""

abstract: Skeletal fluorosis is a chronic metabolic bone disease caused by long-term overconsumption of fluoride, posing a significant health risk to humans globally. However, even professional radiologists cannot accurately determine the severity of lesions in skeletal fluorosis X-rays. Currently, there is limited research on using deep learning to diagnose skeletal fluorosis and no public datasets. Therefore, we construct the world’s first open-source skeletal fluorosis X-ray dataset (SFXRay). To advance the automated grading diagnosis of skeletal fluorosis, we propose a novel convolutional state space model with multi-window cross-scan (Mwinc-Mamba). Mwinc-Mamba adopts a dual-branch structure, integrating the convolutional neural network (CNN) with the state space model (SSM). The CNN branch focuses on extracting local features, whereas the SSM branch models long-range dependencies. This effective combination compensates for the SSM’s shortcoming, excelling at modeling long-range dependencies but not extracting local features. Additionally, we introduce a multi-window cross-scan mechanism in SSM. It divides the patches into multiple windows and performs cross-scan to capture multi-grained lesion features, thereby accurately identifying the severity of lesions. On the SFXRay dataset, the Mwinc-Mamba model achieves diagnostic accuracies of 83.33% and 66.67% for binary and multi-classification respectively, significantly outperforming other deep learning models. Notably, in multi-classification, the accuracy of the Mwinc-Mamba model differs by only 3.33% from the average accuracy of the radiologists, highlighting its strong potential for clinical application.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Medical Image Segmentation
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
    url: "https://doi.org/10.1016/j.bspc.2024.107439"
#  - type: video
#    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Mwinc-Mamba Model Structure Diagram'
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
@article{xu2025convolutional,
title={Convolutional state space model with multi-window cross-scan to advance the automated diagnosis of skeletal fluorosis},
author={Xu, Hao and Wu, Yun and Xie, Rui and Xu, Jun and Wu, Junpeng and Wang, Rongpin and Tian, Youliang},
journal={Biomedical Signal Processing and Control},
volume={103},
pages={107439},
year={2025},
publisher={Elsevier}
} 
```

