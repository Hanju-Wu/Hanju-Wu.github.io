---
title: "SI-ADMM:A stochastic inexact ADMM framework for stochastic convex programs"
collection: publications
permalink: /publication/SI-ADMM-TAC
excerpt: 'Extended journal version of the conference paper under a similar name.'
date: 2019-11-13
venue: 'IEEE Transactions on Automatic Control'
paperurl: 'https://doi.org/10.1109/TAC.2019.2953209'
citation: 'Yue Xie and Uday V. Shanbhag (2019). &quot;SI-ADMM:A stochastic inexact ADMM framework for stochastic convex programs.&quot; <i>IEEE Transactions on Automatic Control</i>. vol. 65, no. 6, pp. 2355-2370.'
---
## Abstract

We consider the structured stochastic convex program requiring the minimization of $E_{\xi} [\tilde{f}(x, \xi)] + E_{\xi} [\tilde{g}(y, \xi)]$ subject to the constraint $Ax+By=b$. Motivated by the need for decentralized schemes and structure, we propose a stochastic inexact ADMM (SI-ADMM) framework where subproblems are solved inexactly via stochastic approximation schemes. Based on this framework, we prove the following: (i) under suitable assumptions on the associated batch-size of samples utilized at each iteration, the SI-ADMM scheme produces a sequence that converges to the unique solution almost surely; (ii) If the number of gradient steps (or equivalently, the number of sampled gradients) utilized for solving the subproblems in each iteration increases at a geometric rate, the mean-squared error diminishes to zero at a prescribed geometric rate; (iii) The overall iteration complexity in terms of gradient steps (or equivalently samples) is found to be consistent with the canonical level of $\mathcal{O}(1/\epsilon)$. Preliminary applications on LASSO and distributed regression suggest that the scheme performs well compared to its competitors.

[Full paper on ArXiv](https://arxiv.org/abs/1711.05286)
