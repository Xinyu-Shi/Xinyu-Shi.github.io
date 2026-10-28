---
title: 'Accurate and Fast Classification of Foot Gestures for Virtual Locomotion'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Junjun Pan
  - Zeyong Hu
  - Juncong Lin
  - Shihui Guo
  - Minghong Liao
  - Ye Pan
  - Ligang Liu

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2019-12-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-01-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: '1'

# Topic group (matches resume grouping; drives the publications filter)
topic: 'Physical Interaction in AR/VR'

# Publication name and optional abbreviated publication name.
honor_tag:
venue_tag: ISMAR 2019
publication: 
publication_short: In Proc. of IEEE International Symposium on Mixed and Augmented Reality 

abstract: This work explores the use of foot gestures for locomotion in virtual environments. Foot gestures are represented as the distribution of plantar pressure and detected by three sparsely-located sensors on each insole. The Long Short- Term Memory model is chosen as the classifier to recognize the performer’s foot gesture based on the captured signals of pressure information. The trained classifier directly takes the noisy and sparse input of sensor data and identifies seven categories of foot gestures (stand, walk forward/backward, run, jump, slide left and right) without the manual definition of signal features. This classifier is capable of recognizing the foot gestures, even with the existence of large sensor-specific, inter-person and intra-person variations. Results show that an accuracy of ∼80% can be achieved across different users with different shoe sizes and ∼85% for users with the same shoe size. A novel method, Dual-Check Till Consensus, is proposed to reduce the latency of gesture recognition from 2 seconds to 0.5 seconds and increase the accuracy to over 97%. This method offers a promising solution to achieve lower latency and higher accuracy at a minor cost of computation workload. The characteristics of high accuracy and fast classification of our method could lead to wider applications of using foot patterns for human-computer interaction.
# Summary. An optional shortened abstract.
summary:  "Key Words: Wearable Technique, Virtual Reality, Gesture Recognition"

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: DOI
  url: https://ieeexplore.ieee.org/document/8943618

# url_pdf: 'https://drive.google.com/uc?export=view&id=1EDIzuGcFtO6126mroKkXUMAtqblzD4sf'
url_pdf: /uploads/ISMAR.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://drive.google.com/uc?export=view&id=1YgF1SUyeOEc7q6qXzUL8ywaroDA213zH

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
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
# teaser_zoom: 1.45
# teaser_offset_y: -1.5
# teaser_offset_x: -5
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
