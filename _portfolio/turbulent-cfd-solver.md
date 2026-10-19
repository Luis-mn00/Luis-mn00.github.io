---
title: "Turbulent CFD Solver (MPI / Multigrid / FDM)"
excerpt: "High-performance FDM solver for the Navier-Stokes equations incorporating turbulence models, MPI parallelization, and geometric multigrid."
collection: portfolio
---

Developed an advanced high-performance numerical solver for the incompressible Navier-Stokes equations in C++ and Python as part of practical coursework at TUM:

* **Turbulence Modeling:** Incorporated mixing length and two-equation $k - \epsilon$ turbulence closure models to simulate realistic turbulent shear flows.
* **HPC & Parallelization:** Implemented 2D/3D spatial domain decomposition with MPI communication for distributed computing clusters.
* **Linear Solvers:** Integrated geometric multigrid (V-cycle, W-cycle) and Preconditioned Conjugate Gradient (PCG) pressure Poisson solvers, drastically improving convergence rates over traditional iterative relaxation methods.
