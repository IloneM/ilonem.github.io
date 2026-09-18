---
title: "Beyond PINNs: A Unified Gauss--Newton and Petrov--Galerkin Framework for Neural and Hybrid PDE Solvers"
collection: publications
category: preprints
permalink: /publication/2026-09-14-Beyond-PINNs-arXiv
excerpt: "We introduce a unified Gauss--Newton and Petrov--Galerkin framework for neural and finite element PDE solvers. This leads both to a Gauss--Newton approach to weak formulations of PINNs and to a hybrid finite element--neural strategy acting on complementary approximation spaces."
date: 2026-09-14
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2609.20641'
citation: 'Nilo Schwencke, Roland Maier, &quot;Beyond PINNs: A Unified Gauss–Newton and Petrov–Galerkin Framework for Neural and Hybrid PDE Solvers.&quot; arXiv preprint arXiv:2609.20641, 2026.'
---

**Abstract:**

Physics-informed neural networks and finite element methods provide two
different paradigms for the numerical approximation of partial differential
equations: the former are commonly trained by minimizing pointwise strong
residuals, whereas the latter are naturally built from weak variational
formulations and the finite-dimensional systems obtained after discretization.
In this work, we introduce a common framework based on the discretization of
functional Gauss--Newton problems by finite families of linear measurements.
We show that, through an appropriate duality pairing, the linear measurements
can be represented by test functions. The resulting Gauss--Newton system is
then precisely a Petrov--Galerkin discretization of the linearized functional
problem. This perspective recovers pointwise collocation and natural-gradient
constructions as particular cases, while making the choice of test functions
an explicit algorithmic design choice. We specialize this framework to
elliptic problems, where it naturally leads to weak residual formulations and
to a projected finite element--neural construction acting on complementary
approximation spaces. Numerical experiments support the proposed framework
and demonstrate the effectiveness of weak Gauss--Newton formulations and
hybrid finite element--neural approximations.

A companion blog post walking through the main ideas is available
[here]({{ base_path }}/tutorials/beyond-pinns-companion).

**BibTeX:**
{% raw %}
```bibtex
@misc{schwencke2026beyond,
      title={Beyond {PINNs}: {A} Unified {Gauss--Newton} and {Petrov--Galerkin} Framework for Neural and Hybrid {PDE} Solvers},
      author={Schwencke, Nilo and Maier, Roland},
      year={2026},
      eprint={2609.20641},
      archivePrefix={arXiv},
      primaryClass={math.NA}
}
```
{% endraw %}
