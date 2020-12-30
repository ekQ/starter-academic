---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Semantically Driven Sentence Fusion: Modeling and Evaluation'
subtitle: ''
summary: ''
authors:
- Eyal Ben-David
- Orgad Keller
- Eric Malmi
- Idan Szpektor
- Roi Reichart
tags: []
categories: []
date: '2020-11-01'
lastmod: 2020-12-30T23:00:42+01:00
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
publishDate: '2020-12-30T22:00:42.143871Z'
publication_types:
- '1'
abstract: Sentence fusion is the task of joining related sentences into coherent text.
  Current training and evaluation schemes for this task are based on single reference
  ground-truths and do not account for valid fusion variants. We show that this hinders
  models from robustly capturing the semantic relationship between input sentences.
  To alleviate this, we present an approach in which ground-truth solutions are automatically
  expanded into multiple references via curated equivalence classes of connective
  phrases. We apply this method to a large-scale dataset and use the augmented dataset
  for both model training and evaluation. To improve the learning of semantic representation
  using multiple references, we enrich the model with auxiliary discourse classification
  tasks under a multi-tasking framework. Our experiments highlight the improvements
  of our approach over state-of-the-art models.
publication: '*Findings of the Association for Computational Linguistics: EMNLP 2020*'
url_pdf: https://www.aclweb.org/anthology/2020.findings-emnlp.135
url_code: https://github.com/eyalbd2/Semantically-Driven-Sentence-Fusion
# doi: 10.18653/v1/2020.findings-emnlp.135
---
