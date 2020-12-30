---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Encode, Tag, Realize: High-Precision Text Editing'
subtitle: ''
summary: ''
authors:
- Eric Malmi
- Sebastian Krause
- Sascha Rothe
- Daniil Mirylenka
- Aliaksei Severyn
tags: []
categories: []
date: '2019-11-01'
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
publishDate: '2020-12-30T22:00:43.696065Z'
publication_types:
- '1'
abstract: 'We propose LaserTagger - a sequence tagging approach that casts text generation
  as a text editing task. Target texts are reconstructed from the inputs using three
  main edit operations: keeping a token, deleting it, and adding a phrase before the
  token. To predict the edit operations, we propose a novel model, which combines
  a BERT encoder with an autoregressive Transformer decoder. This approach is evaluated
  on English text on four tasks: sentence fusion, sentence splitting, abstractive
  summarization, and grammar correction. LaserTagger achieves new state-of-the-art
  results on three of these tasks, performs comparably to a set of strong seq2seq
  baselines with a large number of training examples, and outperforms them when the
  number of examples is limited. Furthermore, we show that at inference time tagging
  can be more than two orders of magnitude faster than comparable seq2seq models,
  making it more attractive for running in a live environment.'
publication: '*Proceedings of the 2019 Conference on Empirical Methods in Natural
  Language Processing and the 9th International Joint Conference on Natural Language
  Processing (EMNLP-IJCNLP)*'
url_pdf: https://www.aclweb.org/anthology/D19-1510
url_code: https://github.com/google-research/lasertagger
url_video: https://vimeo.com/396779285
# doi: 10.18653/v1/D19-1510
---
