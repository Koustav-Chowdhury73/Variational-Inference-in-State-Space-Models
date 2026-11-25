# Finite-Sample Guarantees for Structured Variational Bayes in Hidden Markov Models

## Abstract

Mean-field Variational Inference (MFVI) is often used for estimating the posterior of state variables in state space models for its simplicity. However, improvements to this method are needed for various state space models. Hidden Markov Models (HMMs) have strong dependence among the state variables, and hence a rich yet tractable variational family is needed. To mitigate this issue, we instead propose a Markov-structured variational family for estimating the collapsed posterior of the state variables in both Finite-Categorical and Gaussian-Emission HMMs. We calculate the error of approximation in terms of reverse KL-divergence error and get a clean finite-sample approximation guarantee. For categorical observations with Dirichlet priors and fixed numbers of states and categories, we show that the Kullback-Leibler divergence from a globally optimal structured variational approximation to the exact posterior is O(log(T )) for every observed sequence of length T. For Gaussian observations, we obtain a O(log(T )) upper bound with high probability. We also provide a fixed-point iterative algorithm to implement this method on datasets.

This work is being conducted under the guidance of **Prof. Bodhisattva Sen**, Department of Statistics, Columbia University.
