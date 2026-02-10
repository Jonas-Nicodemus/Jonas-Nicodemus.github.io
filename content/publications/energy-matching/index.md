---
title: 'Energy Matching in Reduced Passive and Port-Hamiltonian Systems'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Tobias Holicki, Paul Schwerdtner, Benjamin Unger

# Author notes (optional)
author_notes: ''

date: '2025-01-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "SIAM Journal on Control and Optimization"
publication_short: "SIAM J. Control Optim. Volume 63, Issue 3, 2025, Pages 2154-2176"

abstract: "
It is well known that any port-Hamiltonian (pH) system is passive, and, conversely, any minimal and stable passive system has a pH representation. Nevertheless, this equivalence is only concerned with the input-output mapping but not with the Hamiltonian itself. Thus, we propose to view a pH system either as an enlarged dynamical system with the Hamiltonian as additional output or as two dynamical systems with the input-output and the Hamiltonian dynamic. Our first main result is a structure-preserving Kalman-like decomposition of the enlarged pH system that separates the controllable and zero-state observable parts. Moreover, for further approximations in the context of structure-preserving model-order reduction (MOR), we propose to search for a Hamiltonian in the reduced pH system that minimizes the $H_2$-distance to the full-order Hamiltonian without altering the input-output dynamic, thus discussing a particular aspect of the corresponding multiobjective minimization problem corresponding to $H_2$-optimal MOR for pH systems. We show that this optimization problem is uniquely solvable and can be recast as a standard semidefinite program, and we present two numerical approaches for solving it. The results are illustrated with three academic examples.
"

# Summary. An optional shortened abstract.
summary:

tags:
  - Port-Hamiltonian Systems
  - Semidefinite Programming
  - Model Order Reduction
  - Nonlinear Optimization

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1137/23M1600931

# Custom links
links:
  # - type: pdf
  #   url: ""
  - type: code
    url: https://github.com/Jonas-Nicodemus/energy-matching
  - type: preprint
    url: https://arxiv.org/abs/2309.05778

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
