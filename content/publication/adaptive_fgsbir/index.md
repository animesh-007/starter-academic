---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Adaptive Fine-Grained Sketch-Based Image Retrieval"
authors: []
date: 2022-07-21T18:40:52+04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-07-21T18:40:52+04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "European Conference on Computer Vision (ECCV) 2022"
publication_short: ""

abstract: "The recent focus on Fine-Grained Sketch-Based Image Re-
trieval (FG-SBIR) has shifted towards generalising a model to new cat-
egories without any training data from them. In real-world applications,
however, a trained FG-SBIR model is often applied to both new cate-
gories and different human sketchers, i.e., different drawing styles. Al-
though this complicates the generalisation problem, fortunately, a hand-
ful of examples are typically available, enabling the model to adapt to the
new category/style. In this paper, we offer a novel perspective – instead
of asking for a model that generalises, we advocate for one that quickly
adapts, with just very few samples during testing (in a few-shot manner).
To solve this new problem, we introduce a novel model-agnostic meta-
learning (MAML) based framework with several key modifications: (1)
As a retrieval task with a margin-based contrastive loss, we simplify the
MAML training in the inner loop to make it more stable and tractable.
(2) The margin in our contrastive loss is also meta-learned with the rest
of the model. (3) Three additional regularisation losses are introduced in
the outer loop, to make the meta-learned FG-SBIR model more effective
for category/style adaptation. Extensive experiments on public datasets
suggest a large gain over generalisation and zero-shot based approaches,
and a few strong few-shot baselines."

# Summary. An optional shortened abstract.
summary: "An Adaptive FG-SBIR model for Fine-Grained Sketch-Based Image Retrieval which adapts to new user category and user hand-drawing style."

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2207.01723
url_code: https://github.com/AyanKumarBhunia/Adaptive-FGSBIR
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
