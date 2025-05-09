# Variance Theory Evolution Framework: Static Demo

[![GitHub](https://img.shields.io/github/license/JulianFrattini/vtef-demo)](./LICENSE)

This repository contains a static version of the web tool for **managing variance theories** in empirical research.
It showcases what the actual, dynamic tool can potentially look like, and serves as an illustration.

## Context

Empirical research disciplines generate evidence about phenomena.
Quantitative pieces of evidence, like effect sizes about the impact of one variable on another, serve as decent decision support, e.g., about whether or not it is efficient to adopt a technique. 
However, synthesizing multiple pieces of quantitative evidence about one phenomenon is non trivial: different analysis methods may be used, replications may come to disagreeing solutions, and causal assumptions about the phenomenon may change.

The variance theory evolution framework[^1] provides a structure and language to describe how two pieces of empirical, quantitative evidence relate to each other.
Additionally, the framework helps to decide which piece of evidence is the most internally valid.

## Structure

This repository contains the following files.

```
├── docs : documentation and specifications
├── figures : visualizations of concepts and graphs
└── src : source code files
```

## License

Copyright © 2025 Julian Frattini. 
This work is licensed under the [Apache-2.0](./LICENSE) license.

[^1]: Frattini, J., Fischbach, J., Fucci, D., Unterkalmsteiner, M., & Mendez, D. (2024). Replications, Revisions, and Reanalyses: Managing Variance Theories in Software Engineering. arXiv preprint [arXiv:2412.12634](https://arxiv.org/abs/2412.12634).
[^2]: Méndez Fernández, D., & Penzenstadler, B. (2015). Artefact-based requirements engineering: the AMDiRE approach. Requirements Engineering, 20, 405-434. DOI: [10.1007/s00766-014-0206-y](https://doi.org/10.1007/s00766-014-0206-y)
