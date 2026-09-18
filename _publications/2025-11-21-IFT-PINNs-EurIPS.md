---
title: "Implicit function theorem in Physics-Informed Neural Networks to solve parameterized differential equations"
collection: publications
category: workshops
permalink: /publication/2025-11-21-IFT-PINNs-EurIPS
excerpt: "We introduce a curriculum-learning strategy for PINNs solving parameterized differential equations. Using an extension of the implicit function theorem, the method follows the solution manifold from an easy problem to a difficult target and connects naturally to natural-gradient optimization."
date: 2025-11-21
venue: 'EurIPS 2025 Workshop DiffSys'
paperurl: 'https://openreview.net/forum?id=KjyGLUleWh'
citation: 'Julien Marie-Anne, Cyriaque Rousselot, Nilo Schwencke, Alena Shilova, &quot;Implicit function theorem in Physics-Informed Neural Networks to solve parameterized differential equations.&quot; EurIPS 2025 Workshop DiffSys, 2025.'
---

**Abstract:**

Physics-informed neural networks (PINNs) have shown promising results in
solving partial differential equations (PDEs). Nevertheless, for some
challenging PDEs, standard PINNs can fail to converge. We propose a novel
curriculum learning strategy that addresses this limitation. Our method
leverages an extension of the implicit function theorem to guide the
training process along the solution manifold of the parameterized
differential equation, starting from an easy-to-solve problem and
progressively moving towards a hard-to-solve one. We establish a
theoretical link between our approach and natural gradient descent, giving
rise to a new effective curriculum learning algorithm allowing us to solve
difficult PDEs such as Eikonal and Hamilton Jacobi-Bellman equations.

**BibTeX:**
{% raw %}
```bibtex
@inproceedings{marieanne2025ift,
  title={Implicit function theorem in {Physics-Informed Neural Networks} to solve parameterized differential equations},
  author={Marie-Anne, Julien and Rousselot, Cyriaque and Schwencke, Nilo and Shilova, Alena},
  booktitle={{EurIPS} 2025 Workshop on Differentiable Systems ({DiffSys})},
  year={2025},
  url={https://openreview.net/forum?id=KjyGLUleWh}
}
```
{% endraw %}