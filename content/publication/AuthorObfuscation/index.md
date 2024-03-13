---
title: "JAMDEC: Unsupervised Authorship Obfuscation using Constrained Decoding over Small Language Models"
authors:
- Jillian Fisher
- Ximing Lu
- Jaehun Jung
- admin
- Zaid Harchaoui
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
publication: NAACL

abstract: "It is commonly perceived that the strongest language models (LMs) rely on a combination of massive scale, instruction data, and human feedback to perform specialized tasks -- e.g., summarization and paraphrasing, without supervision. In this paper, we propose that language models can learn to summarize and paraphrase sentences, with none of these 3 factors. We present Impossible Distillation, a framework that distills a task-specific dataset directly from an off-the-shelf LM, even when it is impossible for the LM itself to reliably solve the task. By training a student model on the generated dataset and amplifying its capability through self-distillation, our method yields a high-quality model and dataset from a low-quality teacher model, without the need for scale or supervision. Using Impossible Distillation, we are able to distill an order of magnitude smaller model (with only 770M parameters) that outperforms 175B parameter GPT-3, in both quality and controllability, as confirmed by automatic and human evaluations. Furthermore, as a useful byproduct of our approach, we obtain DimSum+, a high-quality dataset with 3.4M sentence summaries and paraphrases. Our analyses show that this dataset, as a purely LM-generated corpus, is more diverse and more effective for generalization to unseen domains than all human-authored datasets -- including Gigaword with 4M samples."

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
