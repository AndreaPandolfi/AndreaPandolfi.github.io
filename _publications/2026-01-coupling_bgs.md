---
title: "Linear-cost unbiased posterior estimates for crossed effects and matrix factorization models via couplings"
collection: publications
permalink: /publication/2026-01-coupling_bgs
excerpt: 'In this paper, we show that two-step coupling strategies achieve coalescence times that match the relaxation times of blocked Gibbs-Sampler schemes up to logarithmic factors.'
date: 2026-01-01
venue: 'ArXiv'
paperurl: 'https://arxiv.org/abs/2410.08939'
---

**Abstract:** We design and analyze unbiased Markov chain Monte Carlo (MCMC) schemes based on couplings of blocked Gibbs samplers (BGSs), whose total computational costs scale linearly with the number of parameters and data points. Our methodology is designed for and applicable to high-dimensional BGS with conditionally independent blocks, which are often encountered in Bayesian modeling. We provide bounds on the expected number of iterations needed for coalescence for Gaussian targets, as well as on the tails of the coalescence times distribution. These imply that practical two-step coupling strategies achieve coalescence times that match the relaxation times of the original BGS scheme up to logarithmic factors. To illustrate the practical relevance of our methodology, we apply it to high-dimensional crossed random effect and probabilistic matrix factorization models, for which we develop a novel BGS scheme with improved convergence speed. Our methodology provides unbiased posterior estimates at linear cost (usually requiring only a few BGS iterations for problems with thousands of parameters), matching state-of-the-art procedures for both frequentist and Bayesian estimation of those models.  
You can find the article [here](https://arxiv.org/abs/2410.08939).
