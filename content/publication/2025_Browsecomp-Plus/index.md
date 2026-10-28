---
title: 'BrowseComp-Plus: A More Fair and Transparent Evaluation Benchmark of Deep-Research Agent'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zijian Chen*
  - Xueguang Ma*
  - Shengyao Zhuang*
  - Ping Nie
  - Kai Zou
  - Andrew Liu
  - Joshua Green
  - Kshama Patel
  - Ruoxi Meng
  - Mingyi Su
  - Sahel Sharifymoghaddam
  - Yanxi Li
  - Haoran Hong
  - admin
  - Xuye Liu
  - Nandan Thakur
  - Crystina Zhang
  - Luyu Gao
  - Wenhu Chen
  - Jimmy Lin
  
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-12-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-12-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: '1'

# Topic group (matches resume grouping; drives the publications filter)
topic: 'Generative Models & Agents'

# Publication name and optional abbreviated publication name.
best_tag: 
honor_tag: Spotlight at NeurIPS MTI-LLM Workshop
media_tag: Featured in [**Anthropic Claude Opus 4.5 launch**](https://www.anthropic.com/news/claude-opus-4-5), also adopted by Microsoft, Databricks, IBM Research, etc.
venue_tag: ACL 2026
# venue_tag_2: NeurIPS Workshop
publication: In Proc. of the Annual Meeting of the Association for Computational Linguistics (ACL)
# publication_2: NeurIPS 2025 Workshop on Multi-Turn Interactions in Large Language Models
publication_short: 

abstract: Deep-Research agents, which integrate large language models (LLMs) with search tools, have shown success in improving the effectiveness of handling complex queries that require iterative search planning and reasoning over search results. Evaluations on current benchmarks like BrowseComp relies on black-box live web search APIs, have notable limitations in (1) fairness - dynamic and opaque web APIs hinder fair comparisons and reproducibility of deep research methods; (2) transparency - lack of control over the document corpus makes it difficult to isolate retriever contributions. In other words, the current evaluations may compare a complete deep research system at a given time, but they do not foster well-controlled experiments to provide insights into the capability of underlying deep research LLMs. To address these challenges, we introduce BrowseComp-Plus, a benchmark derived from BrowseComp, employing a fixed, carefully curated corpus. Each query in BrowseComp-Plus includes human-verified supporting documents and mined challenging negatives, enabling controlled experimentation. The benchmark is shown to be effective in distinguishing the performance of deep research systems. For instance, the open-source model Search-R1, when paired with the BM25 retriever, achieves 3.86% accuracy, whereas the GPT-5 achieves 55.9%. Integrating the GPT-5 with the Qwen3-Embedding-8B retriever further enhances its accuracy to 70.1% with fewer search calls. This benchmark allows comprehensive evaluation and disentangled analysis of deep research agents and retrieval methods, fostering insights into retrieval effectiveness, citation accuracy, and context engineering in Deep-Research system.

# Summary. An optional shortened abstract.
summary: "Key Words: Deep-Search Agent, Retrieval, Benchmark"

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
#  url: ''
- name: Paper
  url: 'https://arxiv.org/abs/2508.06600'
# - name: Project Page
#   url: '/uploads/Piet_project_page/index.html'
# - name: ACM DL
#   url: 
url_project: 
url_pdf: 
url_code: 'https://github.com/texttron/BrowseComp-Plus'
url_poster: ''
url_slides:
url_source: 
url_video:
url_dataset:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  placement: 2
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  # - 2020_ASL

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
teaser_zoom: 1.1
teaser_offset_y: -1.6
teaser_offset_x: 0
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
