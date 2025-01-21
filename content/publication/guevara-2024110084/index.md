---
title: 'Uncertainty dynamics in energy planning models: An autoregressive and Markov
  chain modeling approach'
authors:
- Esnil Guevara
- Frédéric Babonneau
- Tito Homem-de-Mello
date: '2024-01-01'
publishDate: '2025-01-21T18:26:15.132179Z'
publication_types:
- article-journal
publication: '*Computers & Industrial Engineering*'
doi: https://doi.org/10.1016/j.cie.2024.110084
abstract: This paper deals with the modeling of stochastic processes in long-term
  multi-stage energy planning problems when limited information is available about
  the distributions of such processes. Starting from simple estimates of variation
  intervals for uncertain parameters, such as energy demands and costs, we model the
  temporal correlation of these parameters through carefully constructed autoregressive
  (AR) models that respect the intervals defined in each period. We introduce a coefficient
  for “zigzag” effects in the evolution of uncertain processes, which controls the
  correlation across periods and also the likelihood of extreme scenarios. To preserve
  the convexity of the stochastic problem, we discretize the AR models associated
  with the cost parameters involved in the objective function by Markov chains. The
  resulting formulation is then solved using a Stochastic Dual Dynamic Programming
  (SDDP) algorithm available in the literature that handles finite-state Markov chains.
  Our numerical experiments, carried out on the Swiss energy system, show a very desirable
  adaptation strategy of investment decisions to uncertainty scenarios, a behavior
  that is not observed when the temporal correlation is ignored. Moreover, the solutions
  lead to better out-of-sample cost performances, especially on extreme scenario realizations,
  than the non-correlated ones which usually result in overcapacities to protect against
  high, but unlikely, parameter variations over time.
tags:
- Energy planning
- Uncertainty modeling
- Temporal correlation
- Autoregressive processes
- Markov chains
- Stochastic dual dynamic programming
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0360835224002055
---
