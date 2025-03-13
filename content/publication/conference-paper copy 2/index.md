---
title: 'Revisiting Point Cloud Completion: Are We Ready For The Real-World?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Prashant Kumar
  - Dheeraj Baiju
  - Nicholus Mboga
  - Gunther Steenackers
  - Rudi Penne

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

# date: '2024-11-26T00:00:00Z'
# doi: 'https://doi.org/10.48550/arXiv.2411.17580'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-26T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: arXiv
publication_short: arXiv

abstract: "Point clouds acquired in constrained, challenging, uncontrolled, and multi-sensor real-world settings are noisy, incomplete, and non-uniformly sparse. This presents acute challenges for the vital task of point cloud completion. Using tools from Algebraic Topology and Persistent Homology (PH), we demonstrate that current benchmark object point clouds lack rich topological features that are integral part of point clouds captured in realistic environments. To facilitate research in this direction, we contribute the first real-world industrial dataset for point cloud completion, RealPC - a diverse, rich and varied set of point clouds. It consists of ~ 40,000 pairs across 21 categories of industrial structures in railway establishments. Benchmark results on several strong baselines reveal that existing methods fail in real-world scenarios. We discover a striking observation - unlike current datasets, RealPC consists of multiple 0- and 1-dimensional PH-based topological features. We prove that integrating these topological priors into existing works helps improve completion. We present how 0-dimensional PH priors extract the global topology of a complete shape in the form of a 3D skeleton and assist a model in generating topologically consistent complete shapes. Since computing Homology is expensive, we present a simple, yet effective Homology Sampler guided network, BOSHNet that bypasses the Homology computation by sampling proxy backbones akin to 0-dim PH. These backbones provide similar benefits of 0-dim PH right from the start of the training, unlike similar methods where accurate backbones are obtained only during later phases of the training."
# Summary. An optional shortened abstract.
summary: 
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://doi.org/10.48550/arXiv.2411.17580

# url_pdf: ''
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
