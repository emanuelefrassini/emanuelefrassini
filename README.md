# Emanuele Frassini

**Applied Mathematics · Scientific Computing · Numerical Methods · Machine Learning for Healthcare**

I'm an applied mathematician with an **MSc in Applied Mathematics from TU Delft** and a **BSc in Mathematical Engineering from Politecnico di Milano**.

My work and interests span **numerical methods for partial differential equations, scientific computing, data assimilation, high-performance computing, and machine learning for clinical workflows**. I focus on making computational work understandable and reproducible through numerical verification, well-documented experiments, and tested research software.

## Publications

- **[Unsupervised multi-modal variational autoencoder for anomaly detection in coronary angiography](https://doi.org/10.1080/13645706.2026.2705585)** — *Minimally Invasive Therapy & Allied Technologies* (2026). **First author.** Unsupervised anomaly detection using video and pose representations of clinical procedures. [Research code](https://github.com/emanuelefrassini/unsupervised_anomaly_detection).
- **[Deep learning methods for clinical workflow phase-based prediction of procedure duration: a benchmark study](https://doi.org/10.1080/24699322.2025.2466426)** — *Computer Assisted Surgery* (2025). **First author.** Benchmarking deep-learning methods for estimating the remaining duration of coronary angiography procedures. [Research code](https://github.com/emanuelefrassini/prediction_procedure_duration).
- **[Automated phase recognition in the cardiac catheterization laboratory with deep learning](https://doi.org/10.1186/s42490-026-00122-x)** — *BMC Biomedical Engineering* (2026). **Joint first author**. Deep-learning classification of coronary angiography workflow phases from multimodal clinical and procedural data.
- **[Benchmarking 2D human pose estimators and trackers for workflow analysis in the cardiac catheterization laboratory](https://doi.org/10.1016/j.medengphy.2025.104289)** — *Medical Engineering & Physics* (2025). **Second author.** Evaluation of markerless human pose estimation and tracking in cardiac catheterization laboratory video.
- **[2D human pose tracking in the cardiac catheterisation laboratory with BYTE](https://doi.org/10.1016/j.medengphy.2024.104270)** — *Medical Engineering & Physics* (2025). **Third author.** Human pose tracking for procedural workflow analysis using geometric pose information.

*Research code is linked where publicly available.*

## Selected scientific-computing projects

| Project | What it demonstrates |
| --- | --- |
| [Tidal Ensemble Kalman Filter](https://github.com/emanuelefrassini/tidal-ensemble-kalman-filter) | Shallow-water modelling, stochastic state estimation, and data assimilation with real water-level observations. |
| [Immersed B-spline FEM](https://github.com/emanuelefrassini/immersed-bspline-fem) | Immersed finite elements, B-spline discretization, Nitsche boundary enforcement, convergence analysis, and cut-cell conditioning. |
| [Multigrid Helmholtz Solvers](https://github.com/emanuelefrassini/multigrid-helmholtz-solvers) | Sparse finite differences, Gauss–Seidel iterations, multigrid V/W-cycles, and spectral analysis. |
| [Overlapping Schwarz Preconditioners](https://github.com/emanuelefrassini/overlapping-schwarz-preconditioners) | One- and two-level domain decomposition, coarse-grid correction, and preconditioned conjugate gradients. |
| [MPI Poisson FEM](https://github.com/emanuelefrassini/mpi-poisson-fem) | Distributed C/MPI computing, finite-element-equivalent operators, and numerical/scaling tests. |
| [CUDA Power Method](https://github.com/emanuelefrassini/cuda-power-method) | GPU computing, dense power iteration, CPU validation, and performance benchmarking. |

**More numerical PDE work:** [Stokes cavity flow (MATLAB/Octave)](https://github.com/emanuelefrassini/stokes-cavity-flow) · [Galerkin vs SUPG advection–diffusion (Python)](https://github.com/emanuelefrassini/advection-diffusion-supg)

## Methods and tools

- **Scientific computing:** Python, NumPy, SciPy, Matplotlib, MATLAB/GNU Octave.
- **Parallel and research software:** C/C++, CUDA, MPI, Git, automated tests, GitHub Actions.
- **Numerical methods:** finite differences, finite elements, B-splines, immersed discretizations, Nitsche's method, iterative linear solvers, multigrid, domain decomposition, ensemble Kalman filtering.
- **Machine learning:** temporal deep learning, representation learning, and clinical workflow modelling.

I use these repositories to document numerical experiments, research implementations, and the process of turning academic coursework into independently testable software.
