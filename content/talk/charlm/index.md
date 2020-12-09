---
title: Token-Free Language Modeling
event: ""
event_url: ""

summary: "How to eliminate segmentation (the last preprocessing step) from NLP models."
abstract: "LSTMs and other RNN variants have shown strong performance on character-level language modeling. These models are typically trained using truncated backpropagation through time, and it is common to assume that their success stems from their ability to remember long-term contexts. In this paper, we show that a deep (64-layer) transformer model with fixed context outperforms RNN variants by a large margin, achieving state of the art on two popular benchmarks: 1.13 bits per character on text8 and 1.06 on enwik8. To get good results at this depth, we show that it is important to add auxiliary losses, both at intermediate network layers and intermediate sequence positions."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-02-01T12:00:00Z"
date_end: "2019-02-01T13:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2019-02-01T13:30:00Z"

authors: [admin]
tags: [Language Modeling, Token-Free]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
url_code: ""
url_pdf: ""
url_slides: "https://docs.google.com/presentation/d/e/2PACX-1vTo_vlM-9V2TwlcwWzwT_PpAy7ixP8UjsUbQyB6qNoH-2DUkcykJy_liJ0vIpC2u6ADzHOKgvYGLx50/embed?start=false&loop=false&delayms=3000"
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
{{< gdocs "https://docs.google.com/presentation/d/e/2PACX-1vTo_vlM-9V2TwlcwWzwT_PpAy7ixP8UjsUbQyB6qNoH-2DUkcykJy_liJ0vIpC2u6ADzHOKgvYGLx50/embed?start=false&loop=false&delayms=3000" >}}

