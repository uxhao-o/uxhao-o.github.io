---
title: "Masked latent transformer with random masking ratio to advance the diagnosis of dental fluorosis"
authors:
- admin
- Yun Wu
- Junpeng Wu
- Rui Xie
- Maohua Gu
- Rongpin Wang
author_notes:
#- "First author"
#- "Corresponding author"
date: "2025-06-05T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-05T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Visual Communication and Image Representation*, 104496"
publication_short: ""

abstract: Dental fluorosis is a chronic condition caused by long-term overconsumption of fluoride, which leads to changes in the appearance of tooth enamel. Diagnosing its severity can be challenging for dental professionals, and limited research on deep learning applications in this field. Therefore, we propose a novel deep learning model, masked latent transformer with random masking ratio (MLTrMR), to advance the diagnosis of dental fluorosis. MLTrMR enhances contextual learning by using a masked latent modeling scheme based on Vision Transformer. It extracts latent tokens from the original image with a latent embedder, processes unmasked tokens with a latent transformer (LT) block, and predicts masked tokens. To improve model performance, we incorporate an auxiliary loss function. MLTrMR achieves state-of-the-art results, with 80.19% accuracy, 75.79% F1 score, and 81.28% quadratic weighted kappa on the first open-source dental fluorosis image dataset (DFID) we constructed.

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
    url: "https://doi.org/10.1016/j.jvcir.2025.104496"
#  - type: video
#    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'MLTrMR Model Structure Diagram'
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
@article{xu2025masked,
  title={Masked latent transformer with random masking ratio to advance the diagnosis of dental fluorosis},
  author={Xu, Hao and Wu, Yun and Wu, Junpeng and Xie, Rui and Gu, Maohua and Wang, Rongpin},
  journal={Journal of Visual Communication and Image Representation},
  pages={104496},
  year={2025},
  publisher={Elsevier}
}
```