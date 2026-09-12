---
title: "Beyond PINNs: From Natural-Gradient Geometry to Hybrid Galerkin Methods"
collection: talks
type: "Conference talk"
permalink: /talks/2027-07-05-BeyondPINNs-ICOSAHOM2027
venue: "16th International Conference on Spectral and High Order Methods (ICOSAHOM 2027)"
date: 2027-07-05
location: "Politecnico di Milano, Milan, Italy"
---

Invited talk proposal at ICOSAHOM 2027, the 16th International Conference on Spectral and High Order Methods (exact day within the conference, held July 5&ndash;9, 2027, TBD).

[Conference website](https://icosahom2027.org/)

**Abstract:**

Physics-informed neural networks and finite-element methods are commonly presented as
fundamentally different paradigms: the former as nonlinear residual minimization, and the latter
as variational projection onto a fixed approximation space. This talk develops a common geometric
and kernel-theoretic framework for both.

A parametrized neural solver defines a finite-dimensional manifold in function space, and natural-gradient training amounts to projecting the functional residual onto its evolving tangent space. By
contrast, a finite-dimensional Galerkin space can be viewed as a flat model manifold and, when
equipped with the energy metric, as a reproducing-kernel Hilbert space whose kernel represents a
projected Green operator.

This viewpoint leads to a reinterpretation of natural-gradient and Gauss–Newton approaches to
PINNs (Müller and Zeinhofer, 2023; Jnini, Vella and Zeinhofer, 2025; Mckay et al., 2025;
Schwencke and Furtlehner, 2025; Schwencke et al., 2025; Urbán, Stefanou and Pons, 2025;
Jnini et al., 2026; Webb, Jerad and Cartis, 2026) as Petrov–Galerkin methods for the linearized
PDE residual, with test functions implicitly induced by the geometry of the neural tangent
space. Once the test space is treated as a design variable, strong collocation can be replaced by
weak and operator-adapted tests. We exploit this freedom to construct a hybrid finite element–neural network in which the finite element component enforces the equation on a stable
approximation space, while the neural network is trained only in its energy-orthogonal
complement. Numerical experiments on multiscale and nonsmooth elliptic problems illustrate
how this decomposition combines the stability of Galerkin methods with the adaptivity of
neural tangent spaces.

The talk concludes with a discussion of residual-reconstruction criteria for adapting the effective
tangent rank and regularizing natural-gradient training.

**References:**

- Jnini, A. et al. (2026) "Curvature-Aware Optimization for High-Accuracy Physics-Informed Neural Networks." arXiv. Available at: [https://doi.org/10.48550/arXiv.2604.05230](https://doi.org/10.48550/arXiv.2604.05230).
- Jnini, A., Vella, F. and Zeinhofer, M. (2025) "Gauss-Newton natural gradient descent for physics-informed computational fluid dynamics," *Computers & Fluids*, p. 106955.
- Mckay, M.B. et al. (2025) "Near-optimal Sketchy Natural Gradients for Physics-Informed Neural Networks." *Forty-second International Conference on Machine Learning*. Available at: [https://openreview.net/forum?id=bKsZomnmqn](https://openreview.net/forum?id=bKsZomnmqn).
- Müller, J. and Zeinhofer, M. (2023) "Achieving high accuracy with PINNs via energy natural gradient descent," *International Conference on Machine Learning*. PMLR, pp. 25471–25485. Available at: [https://proceedings.mlr.press/v202/muller23b.html](https://proceedings.mlr.press/v202/muller23b.html).
- Schwencke, N. et al. (2025) "AMStraMGRAM: Adaptive Multi-cutoff Strategy Modification for ANaGRAM." arXiv. Available at: [https://doi.org/10.48550/arXiv.2510.15998](https://doi.org/10.48550/arXiv.2510.15998).
- Schwencke, N. and Furtlehner, C. (2025) "ANaGRAM: a natural gradient relative to adapted model for efficient PINNs learning," *The Thirteenth International Conference on Learning Representations*. Available at: [https://openreview.net/forum?id=o1IiiNIoaA](https://openreview.net/forum?id=o1IiiNIoaA).
- Urbán, J.F., Stefanou, P. and Pons, J.A. (2025) "Unveiling the optimization process of physics informed neural networks: How accurate and competitive can PINNs be?," *Journal of Computational Physics*, 523, p. 113656. Available at: [https://doi.org/10.1016/j.jcp.2024.113656](https://doi.org/10.1016/j.jcp.2024.113656).
- Webb, J., Jerad, S. and Cartis, C. (2026) "An Optimisation Framework for the Well-Conditioned Training of Physics-Informed Neural Networks." arXiv. Available at: [https://doi.org/10.48550/arXiv.2607.02194](https://doi.org/10.48550/arXiv.2607.02194).
