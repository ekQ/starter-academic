---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Rapformer: Conditional Rap Lyrics Generation with Denoising Autoencoders'
subtitle: ''
summary: ''
authors:
- Nikola I. Nikolov
- Eric Malmi
- Curtis Northcutt
- Loreto Parisi
tags: []
categories: []
date: '2020-12-01'
lastmod: 2020-12-30T23:00:43+01:00
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
publishDate: '2020-12-30T22:00:42.838196Z'
publication_types:
- '1'
abstract: The ability to combine symbols to generate language is a defining characteristic
  of human intelligence, particularly in the context of artistic story-telling through
  lyrics. We develop a method for synthesizing a rap verse based on the content of
  any text (e.g., a news article), or for augmenting pre-existing rap lyrics. Our
  method, called Rapformer, is based on training a Transformer-based denoising autoencoder
  to reconstruct rap lyrics from content words extracted from the lyrics, trying to
  preserve the essential meaning, while matching the target style. Rapformer features
  a novel BERT-based paraphrasing scheme for rhyme enhancement which increases the
  average rhyme density of output lyrics by 10%. Experimental results on three diverse
  input domains show that Rapformer is capable of generating technically fluent verses
  that offer a good trade-off between content preservation and style transfer. Furthermore,
  a Turing-test-like experiment reveals that Rapformer fools human lyrics experts
  25% of the time.
publication: '*Proceedings of the 13th International Conference on Natural Language
  Generation*'
url_pdf: https://www.aclweb.org/anthology/2020.inlg-1.42
---
