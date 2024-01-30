---
title: "Phenomenal Yet Puzzling: Testing Inductive Reasoning Capabilities of Language Models with Hypothesis Refinement"
authors:
- Linlu Qiu
- admin
- Ximing lu
- Melanie Sclar
- Valentina Pyatkin
- Chandra Bhagavatula
- Bailin Wang
- Yoon Kim
- Yejin Choi
- Nouha Dziri
- Xiang Ren
author_notes:



date: "2024-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
# publication: 2022 Annual Conference of the North American Chapter of the Association for Computational Linguistics
# publication_short: NAACL-HLT
publication: ICLR

abstract: "The ability to derive  underlying principles from a handful of observations and then generalize to novel situations---known as inductive reasoning---is central to human intelligence. Prior work suggests that language models (LMs) often fall short on inductive reasoning, despite achieving impressive success on research benchmarks. In this work, we conduct a systematic study of  the inductive reasoning capabilities of LMs through iterative hypothesis refinement, a technique that more closely mirrors  the human inductive process than standard input-output prompting. Iterative hypothesis refinement employs a three-step process: proposing, selecting, and refining hypotheses in the form of textual rules. By examining the intermediate rules, we observe that LMs are phenomenal hypothesis proposers (i.e., generating candidate rules), and when coupled with a (task-specific) symbolic interpreter that is able to systematically filter the proposed set of rules, this hybrid approach achieves strong results across inductive reasoning benchmarks that require inducing causal relations, language-like instructions, and symbolic concepts. However, they also behave as puzzling inductive reasoners, showing notable performance gaps in rule induction (i.e., identifying plausible rules) and rule application (i.e., applying proposed rules to instances), suggesting that LMs are proposing hypotheses without being able to actually apply the rules. Through  empirical and human analyses, we further reveal several discrepancies between the inductive reasoning processes of LMs and humans, shedding light on both the potentials and limitations of using LMs in inductive reasoning tasks."

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
url_pdf: "https://arxiv.org/abs/2310.08559"
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
