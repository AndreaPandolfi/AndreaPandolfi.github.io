---
title: "Approximate filtering via discrete dual processes"
collection: publications
permalink: /publication/2023-10-filtering_discrete_dual_processes
excerpt: 'This paper gives an extensive analysis of approximate (and exact) filtering strategies, when the dual process is a Markov chain on a discrete state space.'
date: 2024-02
venue: 'Stochastic Processes and their Applications'
paperurl: 'https://doi.org/10.1016/j.spa.2023.104268'
---

**Abstract:** We consider the task of filtering a dynamic parameter evolving as a diffusion process, given data collected at discrete times from a likelihood which is conjugate to the reversible law of the diffusion, when a generic dual process on a discrete state space is available. Recently, it was shown that duality with respect to a death-like process implies that the filtering distributions are finite mixtures, making exact filtering and smoothing feasible through recursive algorithms with polynomial complexity in the number of observations. Here we provide general results for the case where the dual is a regular jump continuous-time Markov chain on a discrete state space, which typically leads to filtering distribution given by countable mixtures indexed by the dual process state space. We investigate the performance of several approximation strategies on two hidden Markov models driven by Cox–Ingersoll–Ross and Wright–Fisher diffusions, which admit duals of birth-and-death type, and compare them with the available exact strategies based on death-type duals and with bootstrap particle filtering on the diffusion state space as a general benchmark.

You can find the article [here](https://doi.org/10.1016/j.spa.2023.104268).
