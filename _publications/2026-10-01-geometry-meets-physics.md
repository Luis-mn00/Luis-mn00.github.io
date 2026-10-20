---
title: "Geometry Meets Physics: Data-Efficient Pre-Training for Unstructured Neural PDE Solvers"
collection: publications
category: conferences
permalink: /publication/2026-10-01-geometry-meets-physics
excerpt: 'A disk-data-free pre-training framework combining geometry-driven intrinsic shape descriptors and physics-driven synthetic data for unstructured 3D neural PDE solvers.'
date: 2026-10-01
venue: 'NeurIPS 2026'
paperurl: 'https://arxiv.org/abs/2610.03363'
bibtexurl: '/files/gmp_neurips2026.bib'
header:
  teaser: 'gmp-neurips2026.png'
citation: 'Luis Medrano-Navarro, Giacomo Baldan, Qiang Liu, Benjamin Holzschuh, Jan Hagnberger, Mathias Niepert, Nils Thuerey. (2026). &quot;Geometry Meets Physics: Data-Efficient Pre-Training for Unstructured Neural PDE Solvers.&quot; <i>Advances in Neural Information Processing Systems (NeurIPS 2026)</i>.'
bibtex: |
  @inproceedings{medranonavarro2026geometry,
    title={Geometry Meets Physics: Data-Efficient Pre-Training for Unstructured Neural PDE Solvers},
    author={Medrano-Navarro, Luis and Baldan, Giacomo and Liu, Qiang and Holzschuh, Benjamin and Hagnberger, Jan and Niepert, Mathias and Thuerey, Nils},
    booktitle={Advances in Neural Information Processing Systems (NeurIPS)},
    year={2026},
    url={https://arxiv.org/abs/2610.03363}
  }
---

**Authors:** **Luis Medrano-Navarro**, Giacomo Baldan, Qiang Liu, Benjamin Holzschuh, Jan Hagnberger, Mathias Niepert, Nils Thuerey  
**Conference:** Advances in Neural Information Processing Systems (NeurIPS 2026)  
**Links:** [arXiv:2610.03363](https://arxiv.org/abs/2610.03363) | [Download BibTeX](/files/gmp_neurips2026.bib)

<div style="text-align: center; margin: 1.5em 0;">
  <img src="/images/gmp-neurips2026.png" alt="Geometry Meets Physics - Absolute Error comparison on 3D aircraft mesh (ScrGMP vs GMP)" style="max-width: 80%; max-height: 440px; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.12); border: 1px solid #e2e8f0;">
  <p style="font-size: 0.85em; color: #64748b; margin-top: 0.5em;"><em>Figure: Absolute error comparison on complex 3D aerodynamic geometries. Pre-training with Geometry Meets Physics (GMP) significantly suppresses surface error and accelerates convergence compared to training from scratch (ScrGMP).</em></p>
</div>

### Abstract & Technical Contribution
Neural surrogate models for Partial Differential Equations (PDEs) on unstructured 3D geometries are typically hindered by poor generalization across varying shapes and the exorbitant compute and storage costs of generating pre-computed training simulation runs.

In this work, we present a **disk-data-free pre-training framework** that sidesteps the necessity of storing large-scale simulation libraries on disk:
* **Geometry-Driven Strategy for Steady-State Problems:** Employs intrinsic 3D shape descriptors to enable neural models to learn geometry-informed representations of intricate physical domains directly from shape morphology.
* **Physics-Driven Strategy for Transient Regimes:** Utilizes online generation of synthetic physical states to drive scalable self-supervised and physics-informed pre-training without pre-computed databases.
* **Superior Data Efficiency:** Downstream fine-tuning converges faster, exhibits heightened generalization across unseen geometries, and achieves lower prediction errors in extreme low-data regimes.
