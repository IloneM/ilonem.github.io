---
title: "AMStraMGRAM: Adaptive Multi-cutoff Strategy Modification for ANaGRAM"
collection: publications
category: preprints
permalink: /publication/2025-10-14-AMStraMGRAM
excerpt: "We analyze the training dynamics of ANaGRAM and introduce AMStraMGRAM, an adaptive multi-cutoff strategy for its regularization. A spectral perspective explains the role of regularization and leads to substantial accuracy improvements, reaching machine precision on several benchmark PDEs."
date: 2025-10-14
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2510.15998'
citation: 'Nilo Schwencke, Cyriaque Rousselot, Alena Shilova, Cyril Furtlehner, &quot;AMStraMGRAM: Adaptive Multi-cutoff Strategy Modification for ANaGRAM.&quot; arXiv, 2025.'
---

**Abstract:**

Recent works have shown that natural gradient methods can significantly
outperform standard optimizers when training physics-informed neural
networks (PINNs). In this paper, we analyze the training dynamics of PINNs
optimized with ANaGRAM, a natural-gradient-inspired approach employing
singular value decomposition with cutoff regularization. Building on this
analysis, we propose a multi-cutoff adaptation strategy that further
enhances ANaGRAM's performance. Experiments on benchmark PDEs validate the
effectiveness of our method, which allows to reach machine precision on some
experiments. To provide theoretical grounding, we develop a framework based
on spectral theory that explains the necessity of regularization and extend
previous shown connections with Green's functions theory.

**BibTeX:**
{% raw %}
```bibtex
@misc{schwencke2025amstramgram,
  title={{AMStraMGRAM}: Adaptive Multi-cutoff Strategy Modification for {ANaGRAM}},
  author={Schwencke, Nilo and Rousselot, Cyriaque and Shilova, Alena and Furtlehner, Cyril},
  year={2025},
  eprint={2510.15998},
  archivePrefix={arXiv},
  primaryClass={cs.LG}
}
```
{% endraw %}