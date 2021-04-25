---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'HAConvGNN: Hierarchical Attention Based Convolutional Graph Neural Network
  for Code Documentation Generation in Jupyter Notebooks'
subtitle: ''
summary: ''
authors:
- Xuye Liu
- Dakuo Wang
- April Wang
- Lingfei Wu
tags: []
categories: []
date: '2021-03-31T00:00:00Z'
lastmod: 2021-04-25T19:01:45-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  filename: featured.png
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-04-25T23:01:45.458845Z'
publication_types:
- '3'
abstract: 'Many data scientists use Jupyter notebook to experiment code,
  visualize results, and document rationales or interpretations. The code
  documentation generation CDG task in notebooks is related but different from
  the code summarization task in software engineering, as one documentation
  (markdown cell) may consist of a text (informative summary or indicative
  rationale) for multiple code cells. Our work aims to solve the CDG task by
  encoding the multiple code cells as separated AST graph structures, for which
  we propose a hierarchical attention-based ConvGNN component to augment the
  Seq2Seq network. We build a dataset with publicly available Kaggle notebooks
  and evaluate our model (HAConvGNN) against baseline models (e.g., Code2Seq or
  Graph2Seq).'
publication: '*arXiv preprint arXiv:2104.01002*'

url_pdf: 'https://arxiv.org/pdf/2104.01002.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
