---
title: "Faith and Fate: Limits of Transformers on Compositionality"
authors:
- Nouha Dziri1
- Ximing Lu
- Melanie Sclar
- Xiang Lorraine Li
- admin
- Bill Yuchen Lin
- Peter West
- Chandra Bhagavatula
- Ronan Le Bras
- Jena D. Hwang
- Soumya Sanyal
- Sean Welleck
- Xiang Ren
- Allyson Ettinger
- Zaid Harchaoui
- Yejin Choi
author_notes:
- "Co-first-author"
- "Co-first-author"
- "Co-first-author"
- "Co-second-author"
- "Co-second-author"
- ""
- ""
- ""
- ""
- ""
- ""
- ""
- ""
- ""
- ""
- ""
date: "2023-02-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-24T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
# publication: 2022 Annual Conference of the North American Chapter of the Association for Computational Linguistics
# publication_short: NAACL-HLT
publication: arXiv

abstract: "Transformer large language models (LLMs) have sparked admiration for their exceptional performance on tasks that demand intricate multi-step reasoning. Yet, these models simultaneously show failures on surprisingly trivial problems. This begs the question: Are these errors incidental, or do they signal more substantial limitations? In an attempt to demystify Transformers, we investigate the limits of these models across three representative compositional tasks---multi-digit multiplication, logic grid puzzles, and a classic dynamic programming problem. These tasks require breaking problems down into sub-steps and synthesizing these steps into a precise answer. We formulate compositional tasks as computation graphs to systematically quantify the level of complexity, and break down reasoning steps into intermediate sub-procedures. Our empirical findings suggest that Transformers solve compositional tasks by reducing multi-step compositional reasoning into linearized subgraph matching, without necessarily developing systematic problem-solving skills. To round off our empirical study, we provide theoretical arguments on abstract multi-step reasoning problems that highlight how Transformers' performance will rapidly decay  with increased task complexity."

# Summary. An optional shortened abstract.
summary:

tags:
- NLP
- long paper
- 2023

featured: false
reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?


links:
# https://arxiv.org/abs/2104.06511
# url_pdf: "https://arxiv.org/abs/2212.10465"
# url_slides: pdf/ANION.pdf
#- name: Press
#  url: https://news.stanford.edu/2019/05/08/learning-chatbot-teaches-beats-flashcards/
#  url_code: '#'
#  url_dataset: '#'
# url_poster: 'pdf/ANION.pdf'
#  url_project: ''
# url_slides: 'key/ANION.key'
#url_source: ''
#url_video: 'https://www.youtube.com/embed/xL6_CTiD2DU'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example


---


<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
