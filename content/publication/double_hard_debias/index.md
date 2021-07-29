---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "[Re] Double-Hard Debias: Tailoring Word Embeddings for Gender Bias Mitigation"
authors: [Haswanth Aekula, Sugam Garg,Animesh Gupta]
date: 2021-01-31T01:41:03+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-02-08T01:41:03+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: "ML Reproducibility Challenge 2020"
publication_short: ""

abstract: "Despite widespread use in natural language processing (NLP) tasks, word embeddings have been criticized for inheriting unintended gender bias from training corpora. Previous methods highlight that in word2vec embeddings trained on the Google News dataset, “programmer” is more closely associated with “man” and “homemaker” is more closely associated with “woman”.  Such gender bias has also been shown to propagate in downstream tasks.  Despite plenty of work in this field, with methods ranging from corpus level modification to post-training modifications to embeddings, it remains an unsolved problem. With this work, the authors combine two techniques to reduce gender bias in embeddings. First, they argue that the frequency of words in the corpus adds to the bias. And thus use the work of to remove the frequency component from trained embeddings. Second, they use the hard debias algorithm, to remove the gender direction from the trained embeddings of most biased words. Combining these two techniques, they benchmark the result of their algorithm by showcasing reduction in bias and limited loss of information in the resultant word embeddings."

# Summary. An optional shortened abstract.
summary: '"Programmer” is more closely associated with “man” and “homemaker” is more closely associated with “woman”. Such gender bias has also been shown to propagate in downstream tasks.'

tags: [Gender Bias, Word Embeddings]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2104.06973.pdf
url_code: https://github.com/hassiahk/Double-Hard-Debias
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
  focal_point: "Center"
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
