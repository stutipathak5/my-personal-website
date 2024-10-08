---
title: 'GP-PCS: One-shot Feature-Preserving Point Cloud Simplification with Gaussian Processes on Riemannian Manifolds'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Thomas M. McDonald
  - Seppe Sels
  - Rudi Penne

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-09-07T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2303.15225'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-07T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Accepted in International Conference on Pattern Recognition 2024
publication_short: Accepted in International Conference on Pattern Recognition 2024

abstract: The processing, storage and transmission of large-scale point clouds is an ongoing challenge in the computer vision community which hinders progress in the application of 3D models to real-world settings, such as autonomous driving, virtual reality and remote sensing. We propose a novel, one-shot point cloud simplification method which preserves both the salient structural features and the overall shape of a point cloud without any prior surface reconstruction step. Our method employs Gaussian processes suitable for functions defined on Riemannian manifolds, allowing us to model the surface variation function across any given point cloud. A simplified version of the original cloud is obtained by sequentially selecting points using a greedy sparsification scheme. The selection criterion used for this scheme ensures that the simplified cloud best represents the surface variation of the original point cloud. We evaluate our method on several benchmark and self-acquired point clouds, compare it to a range of existing methods, demonstrate its application in downstream tasks of registration and surface reconstruction, and show that our method is competitive both in terms of empirical performance and computational efficiency. The code is available at https://github.com/stutipathak5/gps-for-point-clouds.
# Summary. An optional shortened abstract.
summary: 
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://doi.org/10.48550/arXiv.2303.15225

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
