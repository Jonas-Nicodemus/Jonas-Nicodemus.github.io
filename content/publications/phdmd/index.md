---
title: 'Port-Hamiltonian Dynamic Mode Decomposition'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Riccardo Morandin, Benjamin Unger

# Author notes (optional)
author_notes: ''

date: '2023-01-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "SIAM Journal on Scientific Computing"
publication_short: "SIAM J. Sci. Comput. Volume 45, Issue A, 2023, Pages A1690-A1710"

abstract: "
We present a novel physics-informed system identification method to construct a passive linear time-invariant system. In more detail, for a given quadratic energy functional, measurements of the input, state, and output of a system in the time domain, we find a realization that approximates the data well while guaranteeing that the energy functional satisfies a dissipation inequality. To this end, we use the framework of port-Hamiltonian (pH) systems and modify the dynamic mode decomposition, respectively, operator inference, to be feasible for continuous-time pH systems. We propose an iterative numerical method to solve the corresponding least-squares minimization problem. We construct an effective initialization of the algorithm by studying the least-squares problem in a weighted norm, for which we present the analytical minimum-norm solution. The efficiency of the proposed method is demonstrated with several numerical examples.
"

# Summary. An optional shortened abstract.
summary:

tags:
  - Port-Hamiltonian Systems
  - Dynamic Mode Decomposition
  - Model Order Reduction
  - Data-Driven Modeling

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1137/22M149329X

# Custom links
links:
  # - type: pdf
  #   url: ""
  - type: code
    url: https://github.com/Jonas-Nicodemus/phdmd
  - type: preprint
    url: https://arxiv.org/abs/2204.13474

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
