---
title: 'CAED-Agent: an Agentic Framework to Automate Simulation-Based Experimental Design'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yang Zhang
  - Yadi Cao
  - Sophia Huiwen Sun
  - Rose Yu


# Author notes (optional)
author_notes:


date: '2024-09-27T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-08-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Under review for *The Fourteenth International Conference on Learning Representations*
publication_short: Under review for *ICLR 2025*

abstract: The adjustment of parameters for expensive computer simulations is a challenging and universal task in the scientific research pipeline. We refer to these problems as Cost-Aware Simulation-Based Experimental Design (CAED). Traditional approaches include a) brute force search, which is prohibitive for high-dimensional parameter combinations; b) Bayesian optimization, which struggles to generalize across setup variations and does not incorporate prior knowledge; c) case-by-case experts designs, which is effective but difficult to scale. Recent work on language models (LLMs) as scientific agents has shown an initial ability to combine pre-trained domain knowledge with tool calling, enabling workflow automation. Naturally, replacing the expert's manual design with this automation seems to be a scalable remedy to general CAED problems. As will be shown in our empirical evaluations, LLMs lack cost awareness for parameter tuning tasks in scientific simulation, leading to poor and inefficient choices. Inference-time scaling approaches enable better exploration, but the massive additional simulator queries they incur add up to total cost and contradict the target of being efficient. To address this challenge, we propose the Cost-Aware Simulation-Based Experimental Design Agent (CAED-Agent), an agentic framework that combines inference-time scaling with the cost-efficiency feedback from a lightweight surrogate model for solving CAED problems. Our experiments in three different simulation cases show that CAED-Agent outperforms both Bayesian optimization and LLM baselines by significant margins, achieving success rates comparable to inference-time scaling with a ground truth simulator, while being far more cost-efficient.

# Summary. An optional shortened abstract.
summary: TL;DR. We present CAED-Agent, a large-language-model agent framework that utilizes inference-time scaling with lightweight surrogate feedback for cost-aware experimental design.

tags:
  - Publish

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.5555/123456

# Custom links
links:
#  - type: pdf
#    url: ""


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

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
slides: ""
---

