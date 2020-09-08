---
title: "Tractable ADMM schemes for computing KKT points and local minimizers for $l_0$-minimization problems"
collection: publications
permalink: /publication/l0min-COAP
excerpt: 'This paper is accepted in August, 2020'
date: 2021-01-01
venue: 'Computational Optimization and Application'
paperurl: 'https://arxiv.org/abs/1710.04613'
citation: 'Yue Xie and Uday V. Shanbhag (2020). &quot;Tractable ADMM schemes for computing KKT points and local minimizers for $\ell_0$-minimization problems.&quot; <i>Computational Optimization and Application</i>.'
---
## Abstract

We consider an $\ell_0$-minimization problem where $f(x)+\gamma \|\| x \|\|0 $ is minimized over a polyhedral set and the $\ell_0$-norm regularizer implicitly emphasizes sparsity of the solution. Such a setting captures a range of problems in image processing and statistical learning. Given the nonconvex and discontinuous nature of this norm, convex regularizers are often employed as substitutes. Therefore, far less is known about directly solving the $\ell_0$-minimization problem. Inspired by [19], we consider resolving an equivalent formulation of the $\ell_0$-minimization problem as a mathematical program with complementarity constraints (MPCC) and make the following contributions towards the characterization and computation of its KKT points: (i) First, we show that feasible points of this formulation satisfy the relatively weak Guignard constraint qualification. Furthermore, under the suitable convexity assumption on $f(x)$, an equivalence is derived between first-order KKT points and local minimizers of the MPCC formulation. (ii) Next, we apply two alternating direction method of multiplier (ADMM) algorithms to exploit special structure of the MPCC formulation: (ADMM$^{\mu,\alpha,\rho}$cf) and (ADMMcf). These two ADMM schemes both have tractable subproblems. Specifically, in spite of the overall nonconvexity, we show that the first of the ADMM updates can be effectively reduced to a closed-form expression by recognizing a hidden convexity property while the second necessitates solving a convex program. In (ADMM$^{\mu,\alpha,\rho}$cf), we prove subsequential convergence to a perturbed KKT point under mild assumptions. Our preliminary numerical experiments suggest that the tractable ADMM schemes are more scalable than their standard counterpart and ADMMcf compares well with its competitors to solve the $\ell_0$-minimization problem.

[Find paper here](https://arxiv.org/abs/1710.04613)
