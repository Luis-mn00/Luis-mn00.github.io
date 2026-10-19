---
title: "Guiding diffusion models to reconstruct flow fields from sparse data"
collection: publications
category: manuscripts
permalink: /publication/2026-01-01-guiding-diffusion-models-flow-fields
excerpt: 'Guided conditional diffusion models to reconstruct high-fidelity 2D and 3D turbulent velocity fields from extremely sparse physical sensor measurements.'
date: 2026-01-01
venue: 'Physics of Fluids'
paperurl: 'https://doi.org/10.1063/5.0304492'
citation: 'Marc Amorós-Trepat*, Luis Medrano-Navarro*, Qiang Liu, Luca Guastoni, Nils Thuerey. (2026). &quot;Guiding diffusion models to reconstruct flow fields from sparse data.&quot; <i>Physics of Fluids</i>, 38(1), 015112. (*Equal contribution).'
---

**Authors:** Marc Amorós-Trepat\*, **Luis Medrano-Navarro**\*, Qiang Liu, Luca Guastoni, Nils Thuerey (\*Equal contribution)  
**Journal:** *Physics of Fluids*, Vol. 38, Issue 1, 015112 (2026)  
**Links:** [DOI: 10.1063/5.0304492](https://doi.org/10.1063/5.0304492) \| [arXiv:2510.19971](https://arxiv.org/abs/2510.19971) \| [Code on GitHub (tum-pbs/sparse-reconstruction)](https://github.com/tum-pbs/sparse-reconstruction)

### Abstract & Technical Contribution
Reconstructing turbulent flow fields from sparse and localized measurement sensors (such as sparse probes or particle image velocimetry) represents a fundamental inverse problem in fluid dynamics with wide applications in experimental aerodynamics and meteorology.

In this work, we propose a conditional guidance strategy for diffusion models:
* **Physics-Guided Reverse Diffusion:** Sparse sensor observations steer the reverse diffusion trajectory, enforcing consistency with available sensor measurements while preserving natural multiscale turbulent statistics.
* **2D & 3D Turbulent Benchmarks:** Demonstrated across challenging turbulent channel flows and isotropic turbulence, recovering small-scale vortex dynamics and turbulent kinetic energy spectra with higher fidelity than traditional linear stochastic estimation or standard supervised convolutional neural networks.
* **Open Science:** Complete PyTorch implementation and pre-trained checkpoints are openly available.
