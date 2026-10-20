---
title: "Solving differential equations with deep learning: a beginner’s guide"
collection: publications
category: manuscripts
permalink: /publication/2024-01-01-solving-differential-equations-deep-learning
excerpt: 'An accessible, comprehensive guide to Physics-Informed Neural Networks (PINNs) for solving ordinary and partial differential equations.'
date: 2024-01-01
venue: 'European Journal of Physics'
paperurl: 'https://doi.org/10.1088/1361-6404/ad0a9f'
bibtexurl: '/files/pinn_guide_ejp2024.bib'
header:
  teaser: 'beginners_guide.png'
citation: 'Luis Medrano-Navarro, Luis Martín Moreno, Sergio G. Rodrigo. (2024). &quot;Solving differential equations with deep learning: a beginner’s guide.&quot; <i>European Journal of Physics</i>, 45(1), 015803.'
bibtex: |
  @article{medranonavarro2024solving,
    title={Solving differential equations with deep learning: a beginner's guide},
    author={Medrano-Navarro, Luis and Mart{\'\i}n-Moreno, Luis and Rodrigo, Sergio G},
    journal={European Journal of Physics},
    volume={45},
    number={1},
    pages={015803},
    year={2024},
    publisher={IOP Publishing},
    doi={10.1088/1361-6404/ad0a9f},
    url={https://doi.org/10.1088/1361-6404/ad0a9f}
  }
---

**Authors:** **Luis Medrano-Navarro**, Luis Martín-Moreno, Sergio G. Rodrigo  
**Journal:** *European Journal of Physics*, Vol. 45, No. 1, 015803 (2024)  
**Links:** [DOI: 10.1088/1361-6404/ad0a9f](https://doi.org/10.1088/1361-6404/ad0a9f) | [arXiv:2307.11237](https://arxiv.org/abs/2307.11237) | [Download BibTeX](/files/pinn_guide_ejp2024.bib)

<div style="text-align: center; margin: 1.5em 0;">
  <img src="/images/beginners_guide.png" alt="Physics-Informed Neural Network prediction vs ground truth" style="max-width: 80%; max-height: 440px; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.12); border: 1px solid #e2e8f0;">
  <p style="font-size: 0.85em; color: #64748b; margin-top: 0.5em;"><em>Figure: Physics-Informed Neural Network (PINN) training dynamics, loss profiles, and analytical solution comparison across ODE and dynamical regimes.</em></p>
</div>

### Abstract & Technical Contribution
Physics-Informed Neural Networks (PINNs) have emerged as a cornerstone methodology in scientific machine learning, enabling neural networks to solve forward and inverse differential problems by integrating differential equations directly into the loss function through automatic differentiation.

This tutorial and review paper provides a pedagogical introduction to PINNs:
* **Core Principles:** Covers continuous-time formulation, loss term composition (governing equations, initial conditions, boundary constraints), and gradient descent dynamics.
* **Practical Examples & Benchmarks:** Step-by-step implementations ranging from classical harmonic oscillators and non-linear pendulum systems to canonical PDEs such as the 1D heat equation and Burger's equation.
* **Practical Best Practices:** In-depth discussion of training stabilization, hyperparameter tuning, loss weighting strategies, and common failure modes for practitioners entering the field.
