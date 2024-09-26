---
title: "HAICOSYSTEM: An Ecosystem for Sandboxing Safety Risks in Human-AI Interactions"
authors:
- Xuhui Zhou
- Hyunwoo Kim
- Faeze Brahman
- admin
- Hao Zhu
- Ximing Lu
- Frank Xu
- Bill Yuchen Lin
- Yejin Choi
- Niloofar Mireshghallah
- Ronan Le Bras
- Maarten Sap
author_notes:
- ""
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

date: "2024-02-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-24T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
# publication: 2022 Annual Conference of the North American Chapter of the Association for Computational Linguistics
# publication_short: NAACL-HLT
publication: Preprint

abstract: "AI agents are increasingly autonomous in their interactions with human users and tools, leading to increased interactional safety risks. We present HAICOSYSTEM, a framework examining AI agent safety within diverse and complex social interactions. HAICOSYSTEM features a modular sandbox environment that simulates multi-turn interactions between human users and AI agents, where the AI agents are equipped with a variety of tools (e.g., patient management platforms) to navigate diverse scenarios (e.g., a user attempting to access other patients' profiles). To examine the safety of AI agents in these interactions, we develop a comprehensive multi-dimensional evaluation framework that uses metrics covering operational, content-related, societal, and legal risks. Through running 1840 simulations based on 92 scenarios across seven domains (e.g., healthcare, finance, education), we demonstrate that HAICOSYSTEM can emulate realistic user-AI interactions and complex tool use by AI agents. Our experiments show that state-of-the-art LLMs, both proprietary and open-sourced, exhibit safety risks in over 50\% cases, with models generally showing higher risks when interacting with simulated malicious users. Our findings highlight the ongoing challenge of building agents that can safely navigate complex interactions, particularly when faced with malicious users. To foster the AI agent safety ecosystem, we release a code platform that allows practitioners to create custom scenarios, simulate interactions, and evaluate the safety and performance of their agents."

# Summary. An optional shortened abstract.
summary:

tags:
- NLP
- long paper
- 2024

featured: false
reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?


links:
# https://arxiv.org/abs/2104.06511
url_pdf: "https://arxiv.org/abs/2409.16427"
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
