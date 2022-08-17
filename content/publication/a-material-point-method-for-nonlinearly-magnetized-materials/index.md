---
title: A Material Point Method for Nonlinearly Magnetized Materials
publication_types:
  - "2"
authors:
  - Yuchen Sun
  - Xingyu Ni
  - Bo Zhu
  - Bin Wang
  - Baoquan Chen
author_notes:
  - Equal Contribution
  - Equal Contribution
  - ""
  - ""
  - Corresponding Author
# Publication name and optional abbreviated publication name.
publication: SIGGRAPH Asia 2021, ACM Transactions on Graphics (TOG)
publication_short: SIGGRAPH Asia 2021, ACM Transactions on Graphics (TOG)
abstract: We propose a novel numerical scheme to simulate interactions between a
          magnetic field and nonlinearly magnetized objects immersed in it. Under
          our nonlinear magnetization framework, the strength of magnetic forces is
          effectively saturated to produce stable simulations without requiring any
          parameter tuning. The mathematical model of our approach is based upon
          Langevin’s nonlinear theory of paramagnetism, which bridges microscopic
          structures and macroscopic equations after a statistical derivation. We devise
          a hybrid Eulerian-Lagrangian numerical approach to simulating this strongly
          nonlinear process by leveraging the discrete material points to transfer both
          material properties and the number density of magnetic micro-particles in
          the simulation domain. The magnetic equations can then be built and solved
          efficiently on a background Cartesian grid, followed by a finite difference
          method to incorporate magnetic forces. The multi-scale coupling can be
          processed naturally by employing the established particle-grid interpolation schemes in a conventional MLS-MPM framework. We demonstrate the
          efficacy of our approach with a host of simulation examples governed by
          magnetic-mechanical coupling effects, ranging from magnetic deformable
          bodies to magnetic viscous fluids with nonlinear elastic constitutive laws.
draft: false
featured: true
image:
  filename: featured.jpg
  focal_point: ''
  preview_only: false
date: 2021-12-01T00:00:00Z
---
