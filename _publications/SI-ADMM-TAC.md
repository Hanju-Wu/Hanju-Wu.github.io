---
title: "SI-ADMM:A stochastic inexact ADMM framework for stochastic convex programs"
collection: publications
permalink: /publication/SI-ADMM-TAC
excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2019-11-13
venue: 'IEEE Transactions on Automatic Control'
paperurl: 'https://doi.org/10.1109/TAC.2019.2953209'
citation: 'Yue Xie and Uday V. Shanbhag (2019). &quot;SI-ADMM:A stochastic inexact ADMM framework for stochastic convex programs.&quot; <i>IEEE Transactions on Automatic Control</i>. vol. 65, no. 6, pp. 2355-2370.'
---
## Abstract

We consider the structured stochastic convex program requiring the minimization of $\mathbb{E}_{\xi} [\bar{f}(x, \xi)] + \mathbb{E}_{\xi} [\bar{g}(y, \xi)]$ subject to the constraint $Ax + By = b$. Motivated by the need for decentralized schemes, we propose a stochastic inexact alternating direction method of multiplier (SI-ADMM) framework where subproblems are solved inexactly via stochastic approximation schemes. we propose a stochastic inexact alternating direction method of multiplier (SI-ADMM) framework where subproblems are solved inexactly via stochastic approximation schemes. Based on this framework, we prove the following: 1) under suitable assumptions on the associated batch-size of samples utilized at each iteration, the SI-ADMM scheme produces a sequence that converges to the unique solution almost surely; 2) if the number of gradient steps (or equivalently, the number of sampled gradients) utilized for solving the subproblems in each iteration increases at a geometric rate, the mean-squared error diminishes to zero at a prescribed geometric rate; and 3) the overall iteration complexity in terms of gradient steps (or equivalently samples) is found to be consistent with the canonical level of $O(1/\epsilon)$. Preliminary applications on LASSO and distributed regression suggest that the scheme performs well compared to its competitors.

[Find paper here](https://doi.org/10.1109/TAC.2019.2953209)
