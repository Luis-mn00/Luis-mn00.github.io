---
title: "Guiding diffusion models to reconstruct flow fields from sparse data"
collection: publications
category: manuscripts
permalink: /publication/2026-01-01-guiding-diffusion-models-flow-fields
excerpt: 'Guided conditional diffusion models to reconstruct high-fidelity 2D and 3D turbulent velocity fields from extremely sparse physical sensor measurements.'
date: 2026-01-01
venue: 'Physics of Fluids'
paperurl: 'https://doi.org/10.1063/5.0304492'
codeurl: 'https://github.com/tum-pbs/sparse-reconstruction'
bibtexurl: '/files/guided_diffusion_pof2026.bib'
header:
  teaser: 'sparse-diffusion-pof2026.png'
citation: 'Marc Amorós-Trepat*, Luis Medrano-Navarro*, Qiang Liu, Luca Guastoni, Nils Thuerey. (2026). &quot;Guiding diffusion models to reconstruct flow fields from sparse data.&quot; <i>Physics of Fluids</i>, 38(1), 015112. (*Equal contribution).'
bibtex: |
  @article{amorostrepat2026guiding,
    title={Guiding diffusion models to reconstruct flow fields from sparse data},
    author={Amor{\'o}s-Trepat, Marc and Medrano-Navarro, Luis and Liu, Qiang and Guastoni, Luca and Thuerey, Nils},
    journal={Physics of Fluids},
    volume={38},
    number={1},
    pages={015112},
    year={2026},
    publisher={AIP Publishing},
    doi={10.1063/5.0304492},
    url={https://doi.org/10.1063/5.0304492}
  }
---

**Authors:** Marc Amorós-Trepat\*, **Luis Medrano-Navarro**\*, Qiang Liu, Luca Guastoni, Nils Thuerey (\*Equal contribution)  
**Journal:** *Physics of Fluids*, Vol. 38, Issue 1, 015112 (2026)  
**Links:** [DOI: 10.1063/5.0304492](https://doi.org/10.1063/5.0304492) | [arXiv:2510.19971](https://arxiv.org/abs/2510.19971) | [GitHub Repository](https://github.com/tum-pbs/sparse-reconstruction) | [Download BibTeX](/files/guided_diffusion_pof2026.bib)

<div style="text-align: center; margin: 1.5em 0;">
  <img src="/images/sparse-diffusion-pof2026.png" alt="Guided diffusion reconstruction of 3D turbulent flow fields" style="max-width: 100%; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.12); border: 1px solid #e2e8f0;">
  <p style="font-size: 0.85em; color: #64748b; margin-top: 0.5em;"><em>Figure: Guided diffusion reconstructing high-fidelity 3D turbulent flow fields from sparse sensor measurements.</em></p>
</div>

### Abstract & Technical Contribution
Reconstructing turbulent flow fields from sparse and localized measurement sensors (such as sparse probes or particle image velocimetry) represents a fundamental inverse problem in fluid dynamics with wide applications in experimental aerodynamics and meteorology.

In this work, we propose a conditional guidance strategy for diffusion models:
* **Physics-Guided Reverse Diffusion:** Sparse sensor observations steer the reverse diffusion trajectory, enforcing consistency with available sensor measurements while preserving natural multiscale turbulent statistics.
* **2D & 3D Turbulent Benchmarks:** Demonstrated across challenging turbulent channel flows and isotropic turbulence, recovering small-scale vortex dynamics and turbulent kinetic energy spectra with higher fidelity than traditional linear stochastic estimation or standard supervised convolutional neural networks.
* **Open Science:** Complete PyTorch implementation and pre-trained checkpoints are openly available.
