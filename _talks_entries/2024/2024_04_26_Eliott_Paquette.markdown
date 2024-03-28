---
author: Eliott Paquette
title: Random matrix theory for high dimensional optimization, and an application to scaling laws
date: 2024-04-26 1:00pm
room: Microsoft Research Labs
---

We describe a program of analysis of stochastic gradient methods on high-dimensional random objectives. We illustrate some assumptions under which the loss curves are universal, in that they can completely be described in terms of some underlying covariances.  Furthermore, we give description of these loss curves that can be analyzed precisely.
We show how this can be applied to SGD on a power-law-random-features model. This is a simple two-hyperparameter family of optimization problems, which displays 5 distinct phases of loss curves; these phases are determined by the relative complexities of the target, data distribution, and whether these are ‘high-dimensional’ or not (which in context can be precisely defined). In each phase, we can also give, for a given compute budget, the optimal random-feature dimensionality.
Joint work with Courtney Paquette (McGill & Google Deepmind), Jeffrey Pennington (Google Deepmind), and Lechao Xiao (Google Deepmind).