---
title: "Inference-Time Policy Adapters (IPA): Tailoring Extreme-Scale LMs without Fine-tuning"
authors:
- Ximing Lu
- Faeze Brahman
- Peter West
- Jaehun Jang
- Khyathi Chandu
- Abhilasha Ravichander
- Lianhui Qin
- Prithviraj Ammanabrolu
- admin
- Sahana Ramnath
- Nouha Dziri
- Jillian Fisher
- Bill Yuchen Lin
- Skyler Hallinan
- Xiang Ren
- Sean Welleck
- Yejin Choi
author_notes:

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

abstract: "Large language models excel at a variety of language tasks when prompted with examples or instructions. Yet controlling these models through prompting alone is limited. Tailoring language models through fine-tuning (e.g., via reinforcement learning) can be effective, but it is expensive and requires model access.
We propose Inference-time Policy Adapters (IPA), which efficiently tailors a language model such as GPT-3 without fine-tuning it. IPA guides a large base model during decoding time through a lightweight policy adaptor trained to optimize an arbitrary user objective with reinforcement learning. 
On five challenging text generation tasks, such as toxicity reduction and open-domain generation, IPA consistently brings significant improvements over off-the-shelf language models. It outperforms competitive baseline methods, sometimes even including expensive fine-tuning. In particular, tailoring GPT-2 with IPA can outperform GPT-3, while tailoring GPT-3 with IPA brings a major performance boost over GPT-3 (and sometimes even over GPT-4). Our promising results highlight the potential of IPA as a lightweight alternative to tailoring extreme-scale language models."

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
url_pdf: "https://arxiv.org/abs/2305.15065"
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
