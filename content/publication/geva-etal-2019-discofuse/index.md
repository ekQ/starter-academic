---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'DiscoFuse: A Large-Scale Dataset for Discourse-Based Sentence Fusion'
subtitle: ''
summary: ''
authors:
- Mor Geva
- Eric Malmi
- Idan Szpektor
- Jonathan Berant
tags: []
categories: []
date: '2019-06-01'
lastmod: 2020-12-30T23:00:44+01:00
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
publishDate: '2020-12-30T22:00:44.112048Z'
publication_types:
- '1'
abstract: 'Sentence fusion is the task of joining several independent sentences into
  a single coherent text. Current datasets for sentence fusion are small and insufficient
  for training modern neural models. In this paper, we propose a method for automatically-generating
  fusion examples from raw text and present DiscoFuse, a large scale dataset for discourse-based
  sentence fusion. We author a set of rules for identifying a diverse set of discourse
  phenomena in raw text, and decomposing the text into two independent sentences.
  We apply our approach on two document collections: Wikipedia and Sports articles,
  yielding 60 million fusion examples annotated with discourse information required
  to reconstruct the fused text. We develop a sequence-to-sequence model on DiscoFuse
  and thoroughly analyze its strengths and weaknesses with respect to the various
  discourse phenomena, using both automatic as well as human evaluation. Finally,
  we conduct transfer learning experiments with WebSplit, a recent dataset for text
  simplification. We show that pretraining on DiscoFuse substantially improves performance
  on WebSplit when viewed as a sentence fusion task.'
publication: '*Proceedings of the 2019 Conference of the North American Chapter of
  the Association for Computational Linguistics: Human Language Technologies, Volume
  1 (Long and Short Papers)*'
url_pdf: https://www.aclweb.org/anthology/N19-1348
url_dataset: https://github.com/google-research-datasets/discofuse
# doi: 10.18653/v1/N19-1348
---
