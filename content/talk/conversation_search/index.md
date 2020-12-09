---
title: Conversation Modeling as a Search Problem
event: ""
event_url: ""

summary: "How to utilize response ranking for conversation modeling."
abstract: "Early Natural Language Understanding systems parsed natural language with hand-crafted rules to explicit semantic representations. These systems are generally limited to the situations imagined by the designer, and much of the development work involves writing more rules. These systems are brittle, and progress is slow leading to narrow-domain applications. Statistical approaches can offer a more forgiving path by learning implicit trade-offs, generalizations, and robust behaviors from data. Deep Learning systems avoid using hand-crafted explicit representations, by learning to map to and from natural language via implicit internal vector representations. In this talk I will show our efforts in using Deep Learning systems in conversation modeling.  We develop an end-to-end system that models written conversations. Such task is hard because not only we need to learn language but also must learn to do something useful with it. Moreover, the learning process requires huge amounts of data, and lots of helpful users to guide the development through live interactions. We currently focus on the subproblem of response suggestion in conversations. We frame natural language response suggestion as a search problem avoiding the need for any natural language generation steps. Inputs are matched with potential responses through a learned semantic metric space. Adding deep layers and delaying combination between input and responses encourages the network to derive implicit semantic representations of the input and responses. We precompute a minimal hierarchy of deep feed-forward networks for all potential responses, and at runtime propagate only the input through the hierarchical network. We use an efficient nearest-neighbor search of the hierarchical embeddings of the responses to find the best suggestions. We study our modeling effort in the context of natural language response suggestion in two domains: Inbox and Reddit."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2017-04-16T12:00:00Z"
date_end: "2017-04-16T13:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-04-16T13:30:00Z"

authors: [admin]
tags: [Conversational Modeling, Deep Retrieval, SmartReply]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
url_code: ""
url_pdf: ""
url_slides: "https://docs.google.com/presentation/d/e/2PACX-1vTWMPlSGXyO_ectt-Vn-1MZdWCMRf85PIwHeZ9hgglte7TRCtoSAojHuT4Ui08ttLBQX_OHbDxSIV5x/embed?start=false&loop=false&delayms=3000"
url_video: ""



# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""


# Enable math on this page?
math: true
---
{{< gdocs "https://docs.google.com/presentation/d/e/2PACX-1vTWMPlSGXyO_ectt-Vn-1MZdWCMRf85PIwHeZ9hgglte7TRCtoSAojHuT4Ui08ttLBQX_OHbDxSIV5x/embed?start=false&loop=false&delayms=3000" >}}

