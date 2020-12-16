---
title: "Watch Your Step: Learning Node Embeddings via Graph Attention"

authors:
- Sami Abu-El-Haija
- Bryan Perozzi
- admin
- Alex Alemi

date: "2018-12-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Neural Information Processing Systems"
publication_short: "NeurIPS-2018"

abstract: "Graph embedding methods represent nodes in a continuous vector space, preserving different types of relational information from the graph. There are many hyperparameters to these methods (e.g. the length of a random walk) which have to be manually tuned for every graph. In this paper, we replace previously fixed hyperparameters with trainable ones that we automatically learn via backpropagation. In particular, we propose a novel attention model on the power series of the transition matrix, which guides the random walk to optimize an upstream objective. Unlike previous approaches to attention models, the method that we propose utilizes attention parameters exclusively on the data itself (e.g. on the random walk), and are not used by the model for inference. We experiment on link prediction tasks, as we aim to produce embeddings that best-preserve the graph structure, generalizing to unseen information. We improve state-of-the-art results on a comprehensive suite of real-world graph datasets including social, collaboration, and biological networks, where we observe that our graph attention model can reduce the error by up to 20%-40%. We show that our automatically-learned attention parameters can vary significantly per graph, and correspond to the optimal choice of hyperparameter if we manually tune existing methods."

# Summary. An optional shortened abstract.
summary:

tags:
- Graph Neural Networks
featured: false

links:
url_pdf: 'https://papers.nips.cc/paper/2018/file/8a94ecfa54dcb88a2fa993bfa6388f9e-Paper.pdf'
url_slides: 'https://docs.google.com/presentation/d/e/2PACX-1vSEDJT1MX_gXD3D8hJxzN5E7bzkOLwOcLbfH2vq7vF_3WTgNbrKZb8QFnhd_0Ev7q2p2eDUiqZK1BAc/pub?start=false&loop=false&delayms=5000&slide=id.ga866723899_0_167'
url_code: 'https://github.com/google-research/google-research/tree/master/graph_embedding/watch_your_step'
url_dataset: ''
url_poster: 'http://sami.haija.org/graph/context/poster.pdf'
url_project: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=nRe5Dg6CiWI'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Learning neigborhood attention instead of assigning a fixed for all graphs.'
  focal_point: ""
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
slides: example
---
