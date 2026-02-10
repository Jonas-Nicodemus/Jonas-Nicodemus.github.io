---
title: 'KLAP: KYP Lemma Based Low-Rank Approximation for $H_2$-Optimal Passivation'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Matthias Voigt, Serkan Gugercin, Benjamin Unger

# Author notes (optional)
author_notes: ''

date: '2026-01-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "SIAM Journal on Matrix Analysis and Applications"
publication_short: "SIAM J. Matrix Anal. Appl. Volume 47, Issue 1, 2026, Pages 1-24"

abstract: "
We present a novel passivity enforcement (passivation) method, called KLAP, for linear time-invariant systems based on the Kalman-Yakubovich-Popov (KYP) lemma and the closely related Lur’e equations. The passivation problem in our framework corresponds to finding a perturbation to a given nonpassive system that renders the system passive while minimizing the $H_2$ or frequency-weighted $H_2$ distance between the original nonpassive and the resulting passive system. We show that this problem can be formulated as an unconstrained optimization problem whose objective function can be differentiated efficiently even in large-scale settings. We show that any minimizer of the unconstrained problem yields the same passive system. Furthermore, we prove that, in the absence of a feedthrough term, every local minimizer is also a global minimizer. For cases involving a nontrivial feedthrough term, we analyze global minimizers in relation to the extremal solutions of the Lur’e equations, which can serve as tools for identifying local minima. To solve the resulting numerical optimization problem efficiently, we propose an initialization strategy based on modifying the feedthrough term and a restart strategy when it is likely that the optimization has converged to a nonglobal local minimum. Numerical examples illustrate the effectiveness of the proposed method.
"

# Summary. An optional shortened abstract.
summary:

tags:
  - Passivation
  - KYP Lemma
  - Nonlinear Optimization

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
    url: https://github.com/Jonas-Nicodemus/klap
  - type: preprint
    url: https://arxiv.org/abs/2501.05178

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
