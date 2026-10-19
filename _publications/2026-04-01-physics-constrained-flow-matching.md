---
title: "Physics-Constrained Adaptive Flow Matching for Climate Downscaling"
collection: publications
category: manuscripts
permalink: /publication/2026-04-01-physics-constrained-flow-matching
excerpt: 'Physics-informed continuous normalizing flows for climate downscaling, enforcing physical conservation laws and boosting calibration.'
date: 2026-04-01
venue: 'Machine Learning: Earth'
paperurl: 'https://arxiv.org/abs/2604.03459'
bibtexurl: '/files/flow_matching_climate2026.bib'
header:
  teaser: 'climate-flow-matching.png'
citation: 'Kevin Debeire, Aytaç Paçal, Pierre Gentine, Luis Medrano-Navarro, Nils Thuerey, Veronika Eyring. (2026). &quot;Physics-Constrained Adaptive Flow Matching for Climate Downscaling.&quot; <i>Machine Learning: Earth</i>.'
bibtex: |
  @article{debeire2026physics,
    title={Physics-Constrained Adaptive Flow Matching for Climate Downscaling},
    author={Debeire, Kevin and Pa{\c{c}}al, Ayta{\c{c}} and Gentine, Pierre and Medrano-Navarro, Luis and Thuerey, Nils and Eyring, Veronika},
    journal={Machine Learning: Earth},
    year={2026},
    doi={10.48550/arXiv.2604.03459},
    url={https://arxiv.org/abs/2604.03459}
  }
---

**Authors:** Kevin Debeire, Aytaç Paçal, Pierre Gentine, **Luis Medrano-Navarro**, Nils Thuerey, Veronika Eyring  
**Journal:** *Machine Learning: Earth*, 2026  
**Links:** [arXiv:2604.03459](https://arxiv.org/abs/2604.03459) | [DOI: 10.48550/arXiv.2604.03459](https://doi.org/10.48550/arXiv.2604.03459) | [Download BibTeX](/files/flow_matching_climate2026.bib)

<div style="text-align: center; margin: 1.5em 0;">
  <img src="/images/climate-flow-matching.png" alt="Physics-Constrained Adaptive Flow Matching for Climate Downscaling visualization" style="max-width: 100%; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.12); border: 1px solid #e2e8f0;">
  <p style="font-size: 0.85em; color: #64748b; margin-top: 0.5em;"><em>Figure: High-resolution downscaling inferences produced by physics-constrained adaptive flow matching.</em></p>
</div>

### Abstract & Technical Contribution
High-resolution climate projections are vital for climate impact assessments, yet physical climate models remain computationally constrained to coarse global resolutions. 

This paper introduces a **physics-constrained adaptive flow matching** formulation tailored to statistical and dynamical downscaling of atmospheric fields:
* **Physics-Informed Priors:** Integrates domain-specific conservation laws (such as mass and moisture budgets) directly into the generative flow matching dynamics.
* **Uncertainty Calibration & Robustness:** Generates well-calibrated probabilistic high-resolution fields while demonstrating strong out-of-distribution robustness under shifting climate scenarios.
* **Empirical Results:** Validated on global reanalysis and regional climate models, showing substantial improvements over standard generative baselines in physical plausibility and fine-scale atmospheric feature recovery.
