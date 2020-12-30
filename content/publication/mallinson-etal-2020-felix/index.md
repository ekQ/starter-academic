---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'FELIX: Flexible Text Editing Through Tagging and Insertion'
subtitle: ''
summary: ''
authors:
- Jonathan Mallinson
- Aliaksei Severyn
- Eric Malmi
- Guillermo Garrido
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
publishDate: '2020-12-30T22:00:41.061489Z'
publication_types:
- '1'
abstract: 'We present FELIX -- a flexible text-editing approach for generation, designed
  to derive maximum benefit from the ideas of decoding with bi-directional contexts
  and self-supervised pretraining. In contrast to conventional sequenceto-sequence
  (seq2seq) models, FELIX is efficient in low-resource settings and fast at inference
  time, while being capable of modeling flexible input-output transformations. We
  achieve this by decomposing the text-editing task into two sub-tasks: tagging to
  decide on the subset of input tokens and their order in the output text and insertion
  to in-fill the missing tokens in the output not present in the input. The tagging
  model employs a novel Pointer mechanism, while the insertion model is based on a
  Masked Language Model (MLM). Both of these models are chosen to be non-autoregressive
  to guarantee faster inference. FELIX performs favourably when compared to recent
  text-editing methods and strong seq2seq baselines when evaluated on four NLG tasks:
  Sentence Fusion, Machine Translation Automatic Post-Editing, Summarization, and
  Text Simplification'
publication: '*Findings of the Association for Computational Linguistics: EMNLP 2020*'
url_pdf: https://www.aclweb.org/anthology/2020.findings-emnlp.111
# doi: 10.18653/v1/2020.findings-emnlp.111
---
