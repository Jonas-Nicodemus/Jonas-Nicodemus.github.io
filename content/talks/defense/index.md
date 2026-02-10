---
title: "Applied optimization techniques for port-Hamiltonian systems"
date: '2025-12-04T00:00:00Z'

event_name: Doctoral defense
event_url: ''

location: University of Stuttgart
address:
  street: Room 8.122, Pfaffenwaldring 57
  city: Stuttgart
  postcode: '70569'
  country: Germany

summary: "Defense of my doctoral thesis on: \"Applied optimization techniques for port-Hamiltonian systems.\""
abstract: |
  This thesis explores various challenges associated with passive and port-Hamiltonian (pH) systems.
  The first part focuses on constructing pH systems from data, considering two principal strategies: preserving the pH structure throughout the construction process or enforcing this structure post hoc on an unstructured model.

  Building upon the Dynamic Mode Decomposition framework, we first adapt the underlying least-squares problem to incorporate the pH structure and propose a tailored optimization algorithm.

  Subsequently, we address the case where an unstructured (non-passive) model is given. To impose the pH structure — more generally, passivity — we develop a method that perturbs the system’s output matrix. This approach employs a novel parametrization of passive systems based on the KYP lemma and utilizes a gradient-based optimization technique to determine the perturbation. As the resulting optimization problem is non-convex, we propose strategies for avoiding or escaping local minima.

  In the second part, we present a new perspective on model order reduction (MOR) for pH systems by incorporating the approximation of the Hamiltonian. To this end, we extend the classical pH class by treating the Hamiltonian as an additional output, thereby falling within the broader class of linear systems with quadratic output.

  A two-stage MOR approach for the extended pH system is then proposed: first, conventional structure-preserving MOR is performed, followed by an optimization of the Hamiltonian formulated as a convex optimization problem.

  For each proposed method, numerical experiments are conducted to illustrate and validate the effectiveness and practical utility of the approaches.

# Talk start and end times.
event_start: '2025-12-04T15:00:00Z'
event_end: '2025-12-04T17:00:00Z'
event_all_day: false

authors:
  - me

tags:
  - Doctoral Defense
  - Optimization
  - Port-Hamiltonian Systems
  - Model Order Reduction

featured: true

image:
  caption: ''
  focal_point: Right

links: []

# Link to your Markdown slides
slides: ''

projects: []
---
