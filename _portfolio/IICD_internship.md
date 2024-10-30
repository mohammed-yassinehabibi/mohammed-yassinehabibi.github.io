---
title: "Deep-Learning and Approximate Bayesian Computation for Finite Site model multivariate inference"
paperurl: 'http://mohammed-yassinehabibi.github.io/files/EA_Recherche_Rapport_final.pdf'
collection: portfolio
---


Find the repository with all the material to reproduce the experiments [here](https://github.com/mohammed-yassinehabibi/MSPIDNA-SMC-ABC-RF). \\
Understanding the mechanisms of DNA molecule evolution and mutation, both over population evolutionary time scales and within the human lifespan, is of significant scientific interest. We will focus on DNA molecules suspected to have biased transition parameters (where certain nucleotide substitutions are more favored than others) and those that should be studied using a finite-sites approach. To understand the behavior of a set of cells of interest, we will rely on multi-parametric stochastic evolutionary models that take multiple parameters as input and produce nucleotide sequences sampled from a population of individuals or cells as output.
At first, we will propose a method to summarize complex and large genomic data into a vector of low-dimensional summary statistics using a deep learning algorithm inspired by Sanchez et al. 2021 and that we adapted to handle nucleotide sequences that differentiate the A, T, C, and G bases. In a second stage, we will perform an inference task to fit the parameters of a stochastic model to our study data. To do this, we will use an adaptive sequential Monte Carlo algorithm, where each step involves running an approximate Bayesian computation random forest algorithm that uses simulated data to derive an increasingly precise posterior distribution.
Our results will show our algorithm’s ability of inferring parameters for a finite site model generating sequences with multiple non-visible mutations.