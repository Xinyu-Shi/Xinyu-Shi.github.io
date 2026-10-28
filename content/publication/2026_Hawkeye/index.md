---
title: 'Hawkeye: Inspecting Agentic Search Trajectories'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Crystina Zhang
  - Zigeng Xu
  - admin
  - Raphael Tang
  - Nandan Thakur
  - Xueguang Ma
  - Yao Lu
  - Jimmy Lin
  
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-01-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: '1'

# Topic group (matches resume grouping; drives the publications filter)
topic: 'Generative Models & Agents'

# Publication name and optional abbreviated publication name.
best_tag: 
honor_tag: 
venue_tag: SIGIR-AP 2026
publication: In Proc. of the ACM SIGIR Conference on Information Retrieval in the Asia Pacific
publication_short: 

# abstract: Agentic search systems answer complex questions by iteratively issuing subqueries, retrieving evidence, and deciding whether and how to continue the search. However, existing evaluations often reduce this process to final accuracy or the number of search calls, obscuring whether an agent is exploring useful topics, reusing prior evidence, or wasting context on redundant documents. We present HAWKEYE, a visual analytics tool for inspecting agentic search trajectories at both the per-question and dataset levels. HAWKEYE records each question, LLM-issued subquery, and retrieved document, and visualizes three complementary aspects: topic shift across subqueries, query provenance attributing query tokens to the original question, retrieved context, LLM parametric memory, or previous queries, and document novelty measuring how many retrieved documents in each round are new rather than repeated from earlier rounds. Using HAWKEYE to analyze BrowseComp-Plus runs, we identify behaviors that are difficult to observe from aggregate metrics alone, including repeated retrieval of previously seen documents and sparsely use newly retrieved context in query formulation. These observations show how trajectory visualization can help diagnose agentic search failures and suggest directions for improving agentic search systems.

# Summary. An optional shortened abstract.
# summary: "Key Words: Agentic Search, Trajectory Inspection"

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
#  url: ''
# - name: DOI
#   url: 'https://doi.org/10.1145/3706599.3720182'
# - name: Project Page
#   url: '/uploads/Piet_project_page/index.html'
# - name: ACM DL
#   url: 
url_project: 
url_pdf: 'https://crystina-z.github.io/manuscripts/zhang-etal-2025-haweye.pdf'
url_code: 
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
  placement: 1
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
teaser_zoom: 1.25
teaser_offset_y: 7
teaser_offset_x: 0
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
