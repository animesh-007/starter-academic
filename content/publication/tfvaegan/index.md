---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "[Re] Latent Embedding Feedback and Discriminative Featuresfor Zero-Shot Classification (Under Review)"
authors: [Animesh Gupta, Aditya Arora, Syed Waqas Zamir]
date: 2021-07-29T15:37:47+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-07-29T15:37:47+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: "ML Reproducibility Challenge 2021 Spring Edition"
publication_short: ""

abstract: "Zero-shot learning (ZSL) is a challenging vision task that involves classifying images into new 'unseen' categories at test time, without having been provided any corresponding visual example during training. Most recent work in ZSL and GZSL recognition are based on Generative Adversarial Networks (GANs), where a generative model is learned using the seen class feature instances and the corresponding class-specific semantic embeddings. Feature instances of the unseen categories, whose real features are unavailable during training, are then synthesized using the trained GAN and used along with the real feature instances from the seen categories to train zero-shot classifiers in a fully-supervised setting. In this reproducibility report, we study the proposed work by Narayan et al. [2020] in detail, which consists of implementing the architecture described in the paper, running experiments, reporting the important details about certain issues encountered during reproducing, and comparing the obtained results with the ones reported in the original paper. We report our numbers on seen accuracy, unseen accuracy and Harmonic mean."

# Summary. An optional shortened abstract.
summary: "TF-VAEGAN proposes to enforce a semantic embedding decoder (SED) at training, feature synthesis and classification stages of (generalized) zero-shot learning."

tags: [Zero-Shot learning, Computer Vision]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://drive.google.com/file/d/1Xd4qCYkZo2JvLcA_F6pnLEE7AEO21u50/view?usp=sharing
url_code: https://github.com/channelCS/ZSL_Generative
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "center"
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
