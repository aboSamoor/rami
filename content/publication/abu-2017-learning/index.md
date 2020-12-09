---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning edge representations via low-rank asymmetric projections
subtitle: ''
summary: ''
authors:
- Sami Abu-El-Haija
- Bryan Perozzi
- Rami Al-Rfou
tags: []
categories: []
date: '2017-01-01'
lastmod: 2020-12-08T18:08:29-08:00
featured: false
draft: false


url_pdf: 'https://arxiv.org/pdf/1705.05615.pdf'
url_code: 'https://github.com/google/asymproj_edge_dnn'

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
publishDate: '2020-12-09T02:08:29.836062Z'
publication_types:
- '1'
abstract: 'We propose a new method for embedding graphs while preserving directed edge information. Learning such continuous-space vector representations (or embeddings) of nodes in a graph is an important first step for using network information (from social networks, user-item graphs, knowledge bases, etc.) in many machine learning tasks.</br> Unlike previous work, we (1) explicitly model an edge as a function of node embeddings, and we (2) propose a novel objective, the "graph likelihood", which contrasts information from sampled random walks with non-existent edges. Individually, both of these contributions improve the learned representations, especially when there are memory constraints on the total size of the embeddings. When combined, our contributions enable us to significantly improve the state-of-the-art by learning more concise representations that better preserve the graph structure.</br> We evaluate our method on a variety of link-prediction task including social networks, collaboration networks, and protein interactions, showing that our proposed method learn representations with error reductions of up to 76% and 55%, on directed and undirected graphs. In addition, we show that the representations learned by our method are quite space efficient, producing embeddings which have higher structure-preserving accuracy but are 10 times smaller.'
publication: '*Proceedings of the 2017 ACM on Conference on Information and Knowledge
  Management*'
---
