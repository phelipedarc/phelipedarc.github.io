---
title: "Kilonova Spectral Inverse Modelling with Simulation-Based Inference: An Amortized Neural Posterior Estimation Analysis"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'Kilonovae represent a category of astrophysical transients, identifiable as the electromagnetic observable counterparts associated with the coalescence events of binary systems comprising neutron stars and neutron star-black hole pairs.
They act as probes for heavy-element nucleosynthesis in astrophysical environments. These studies rely on inference of the physical parameters (e.g., ejecta mass, velocity, composition) that describe kilonovae based on electromagnetic observations. This is a complex inverse problem typically addressed with sampling-based methods such as Markov-chain Monte Carlo (MCMC) or nested sampling algorithms. 
However,  repeated inferences can be computationally expensive due to the sequential nature of these methods. This poses a significant challenge to ensuring the reliability and statistical validity of the posterior approximations and, thus, the inferred kilonova parameters themselves. We present a novel approach: Simulation-Based Inference (SBI) using simulations produced by \texttt{KilonovaNet}. Our method employs an ensemble of Amortized Neural Posterior Estimation (ANPE) with an embedding network to directly predict posterior distributions from simulated spectral energy distributions (SEDs). We take advantage of the quasi-instantaneous inference time of ANPE to demonstrate the reliability of our posterior approximations using diagnostics tools, including coverage diagnostic and posterior predictive checks.  We further test our model with real observations from AT\,2017gfo, the only kilonova with multi-messenger data, demonstrating agreement with previous likelihood-based methods while reducing inference time down to a few seconds. The inference results produced by ANPE appear to be conservative and reliable, paving the way for testable and more efficient kilonova parameter inference.'
date: 2024-02-17
paperurl: '[http://academicpages.github.io/files/paper3.pdf](https://arxiv.org/abs/2311.09471)'
citation: 'Darc et al 2024'
---

