---
title: "Integrated method for grading diagnosis of dental fluorosis combined with segmentation and classification"
authors:
- Maohua Gu
- Yun Wu
- Zhongchuan Jiang
- admin
#author_notes:
#- "First author"
#- "Corresponding author"
date: "2024-10-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Biomedical Signal Processing and Control* 96 (2024): 106510"
publication_short: ""

abstract: Endemic fluorosis is chronic fluorosis caused by excessive accumulation of fluorine in the body. The early symptom of fluoride toxicity is dental fluorosis. In severe cases of poisoning, it can lead to skeletal fluorosis. Screening for fluorosis is conducted almost yearly in remote fluorosis areas, but the lack of medical resources often leads to misdiagnosis or missed diagnosis. Therefore, applying deep learning technology to diagnose dental fluorosis is significant. Through field research and literature review, we discovered that the current screening for dental fluorosis relies entirely on doctors’ knowledge and experience without applying deep learning in relevant studies on automated diagnosis. Based on the analysis of images, we noted that the lesions display irregular shapes and indistinct borders. Additionally, the appearance of lesions can be influenced by various factors, such as extrinsic staining and illuminance. They present challenges in diagnosing dental fluorosis. So, we proposed a two-stage methodology for grading the diagnosis of dental fluorosis. In the first stage, we proposed an improved U-Net based on large kernel convolution for tooth region segmentation. Additionally, we designed a pixel-association iterative algorithm to optimize the segmentation results. In the second stage, we devised a dual-branch fusion classifier based on CNN and Transformer, which ensured accurate classification even when the lesion features occupy only a tiny proportion of the entire image. We established the first dental fluorosis dataset and evaluated our proposed method, which has achieved satisfactory results in the grading diagnosis of dental fluorosis after conducting many experiments.
  
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Medical Image Analysis
featured: false

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
    url: "https://doi.org/10.1016/j.bspc.2024.106510"
#  - type: video
#    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Model Structure Diagram'
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
@article{gu2024integrated,
  title={Integrated method for grading diagnosis of dental fluorosis combined with segmentation and classification},
  author={Gu, Maohua and Wu, Yun and Jiang, Zhongchuan and Xu, Hao},
  journal={Biomedical Signal Processing and Control},
  volume={96},
  pages={106510},
  year={2024},
  publisher={Elsevier}
}
```

