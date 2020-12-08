---
title: "LAReQA: Language-agnostic answer retrieval from a multilingual pool"

authors:
- Uma Roy
- Noah Constant
- admin
- Aditya Barua
- Aaron Phillips
- Yinfei Yang

date: "2020-04-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 2020 Conference on Empirical Methods in Natural Language Processing"
publication_short: "EMNLP 2020"

abstract: We present LAReQA, a challenging new benchmark for language-agnostic answer retrieval from a multilingual candidate pool. Unlike previous cross-lingual tasks, LAReQA tests for “strong” cross-lingual alignment, requiring semantically related cross-language pairs to be closer in representation space than unrelated same-language pairs. This level of alignment is important for the practical task of cross-lingual information retrieval. Building on multilingual BERT (mBERT), we study different strategies for achieving strong alignment. We find that augmenting training data via machine translation is effective, and improves significantly over using mBERT outof-the-box. Interestingly, model performance on zero-shot variants of our task that only target “weak” alignment is not predictive of performance on LAReQA. This finding underscores our claim that language-agnostic retrieval is a substantively new kind of crosslingual evaluation, and suggests that measuring both weak and strong alignment will be important for improving cross-lingual systems going forward. We release our dataset and evaluation code at https://github.com/google-research-datasets/lareqa

# Summary. An optional shortened abstract.
summary:

tags:
- Multilingual
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.aclweb.org/anthology/2020.emnlp-main.477.pdf'
url_code: ''
url_dataset: 'https://github.com/google-research-datasets/lareqa'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'A weakly aligned multilingual embedding space enables zero-shot transfer between languages, but incorrect answers in the same language are preferred over correct answers in a different language. A strongly aligned embedding space “factors out” language, so the most semantically relevant pairs are always the closest, regardless of language.'
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
