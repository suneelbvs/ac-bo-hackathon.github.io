---
number: 1 # leave as-is, maintainers will adjust
title: Bayesian Optimization for Generality
topic: general
team_leads:
  - Felix Strieth-Kalthoff (University of Toronto)

contributors:
  - 

github: AC-BO-Hackathon/general-optimizers
# youtube_video: <your-video-id>

---

This project focuses on benchmarks and algorithms for “generality-oriented” Bayesian Optimization (BO). Usually, BO works by identifying those parameters x that optimize a single objective $f(\bold{x})$. However, in the natural sciences, problems often involve several related objectives ${f_i(\bold{x})}_{i=1}^n$. Here, the aim is to find parameters $\bold{x}$ that do well across all these objective functions, without evaluating each $f_i(\bold{x})$ in every iteration. A particularly important example of this is chemical reaction optimization, where the goal is to find reaction conditions that work well across a broad range of substrates. While recent years have seen early examples of generality-oriented BO, our goal is to establish benchmark tasks for generality-oriented BO, evaluate existing strategies, and develop new algorithms for generality-oriented BO (building on ideas from multi-fidelity optimization). 

References:

1. N. H. Angello et al. Science 2022, 378, 399. https://doi.org/10.1126/science.adc8743 
2. J. Y. Wang et al. Nature 2024, 626, 1025. https://doi.org/10.1038/s41586-024-07021-y 
