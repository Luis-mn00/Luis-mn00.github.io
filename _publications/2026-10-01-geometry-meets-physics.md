---
title: "Geometry Meets Physics: Data-Efficient Pre-Training for Unstructured Neural PDE Solvers"
collection: publications
category: conferences
permalink: /publication/2026-10-01-geometry-meets-physics
excerpt: 'A disk-data-free pre-training framework combining geometry-driven intrinsic shape descriptors and physics-driven synthetic data for unstructured 3D neural PDE solvers.'
date: 2026-10-01
venue: 'Advances in Neural Information Processing Systems (NeurIPS 2026)'
paperurl: 'https://arxiv.org/abs/2610.03363'
citation: 'Luis Medrano-Navarro, Giacomo Baldan, Qiang Liu, Benjamin Holzschuh, Jan Hagnberger, Mathias Niepert, Nils Thuerey. (2026). &quot;Geometry Meets Physics: Data-Efficient Pre-Training for Unstructured Neural PDE Solvers.&quot; <i>Advances in Neural Information Processing Systems (NeurIPS 2026)</i>.'
---

**Authors:** **Luis Medrano-Navarro**, Giacomo Baldan, Qiang Liu, Benjamin Holzschuh, Jan Hagnberger, Mathias Niepert, Nils Thuerey  
**Conference:** Advances in Neural Information Processing Systems (NeurIPS 2026)  
**Links:** [arXiv:2610.03363](https://arxiv.org/abs/2610.03363)

### Abstract & Technical Contribution
Neural surrogate models for Partial Differential Equations (PDEs) on unstructured 3D geometries are typically hindered by poor generalization across varying shapes and the exorbitant compute and storage costs of generating pre-computed training simulation runs.

In this work, we present a **disk-data-free pre-training framework** that sidesteps the necessity of storing large-scale simulation libraries on disk:
* **Geometry-Driven Strategy for Steady-State Problems:** Employs intrinsic 3D shape descriptors to enable neural models to learn geometry-informed representations of intricate physical domains directly from shape morphology.
* **Physics-Driven Strategy for Transient Regimes:** Utilizes online generation of synthetic physical states to drive scalable self-supervised and physics-informed pre-training without pre-computed databases.
* **Superior Data Efficiency:** Downstream fine-tuning converges faster, exhibits heightened generalization across unseen geometries, and achieves lower prediction errors in extreme low-data regimes.
