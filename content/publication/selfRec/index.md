---
title: 'Self-Recognition in Language Models'

# Authors
authors:
  - Tim R. Davidson
  - Viacheslav Surkov
  - Veniamin Veselovsky
  - Giuseppe Russo
  - Robert West
  - Caglar Gulcehre

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-11-01T00:00:00Z'
publishDate: '2024-11-01T00:00:00Z'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Findings of the Association for Computational Linguistics: EMNLP 2024*
publication_short: In *EMNLP Findings 2024*

abstract: |
  A rapidly growing number of applications rely on a small set of closed-source language models (LMs). This dependency might introduce novel security risks if LMs develop self-recognition capabilities. Inspired by human identity verification methods, we propose a novel approach for assessing self-recognition in LMs using model-generated “security questions.” Our test can be externally administered without access to internal model parameters or output probabilities. We apply this test to ten of the most capable open- and closed-source LMs available. Our experiments find no empirical evidence of consistent self-recognition. Instead, models tend to select the “best” answer, independent of authorship. We further find that preferences for certain model outputs are consistent across LMs, and we uncover new insights about position bias in multiple-choice tasks.

summary: |
  We introduce a novel test for self-recognition in language models and show that current frontier LMs do not consistently recognize their own outputs. Models instead prefer answers they perceive as best, regardless of source.

tags:
  - Language Models
  - AI Safety
  - Model Evaluation
  - Identity Verification
  - EMNLP

# Display this page in the Featured widget?
featured: false

# Custom links
url_pdf: 'https://aclanthology.org/2024.findings-emnlp.703.pdf'
doi: '10.18653/v1/2024.findings-emnlp.703'

# Media coverage (optional, add if applicable)
# media_coverage:
#   - title: 'Example Media Coverage Title'
#     url: 'https://example.com/article-url'

# Featured image
image:
  caption: ''
  focal_point: ''
  preview_only: false
---
