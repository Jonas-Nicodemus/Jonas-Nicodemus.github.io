---
title: 'Physics-Informed Neural Networks-based Model Predictive Control for Multi-link Manipulators'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Jonas Kneifl, Jörg Fehr, Benjamin Unger

# Author notes (optional)
author_notes: ''

date: '2013-07-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "In *10th Vienna International Conference on Mathematical Modelling MATHMOD: 2022 Vienna Austria, 27–29 July 2022*"
publication_short: "In *IFAC-PapersOnLine Volume 55, Issue 20, 2022, Pages 331-336*"

abstract: "We discuss nonlinear model predictive control (MPC) for multi-body dynamics via physics-informed machine learning methods. In more detail, we use a physics-informed neural networks (PINNs)-based MPC to solve a tracking problem for a complex mechanical system, a multi-link manipulator. PINNs are a promising tool to approximate (partial) differential equations but are not suited for control tasks in their original form since they are not designed to handle variable control actions or variable initial values. We thus follow the strategy of Antonelo et al. (arXiv:2104.02556, 2021) by enhancing PINNs with adding control actions and initial conditions as additional network inputs. Subsequently, the high-dimensional input space is reduced via a sampling strategy and a zero-hold assumption. This strategy enables the controller design based on a PINN as an approximation of the underlying system dynamics. The additional benefit is that the sensitivities are easily computed via automatic differentiation, thus leading to efficient gradient-based algorithms for the underlying optimal control problem."

# Summary. An optional shortened abstract.
summary:

tags:
  - Physics-Informed Neural Networks
  - Model Predictive Control
  - Robotics

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1016/j.ifacol.2022.09.117

# Custom links
links:
  # - type: pdf
  #   url: ""
  - type: code
    url: https://github.com/Jonas-Nicodemus/PINNs-based-MPC
  - type: preprint
    url: https://arxiv.org/abs/2109.10793

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
