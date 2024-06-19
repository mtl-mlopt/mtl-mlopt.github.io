---
author: Samuel Vaiter
title: "(Automatic) Iterative Differentiation: some old (& new) results"
date: 2024-06-26 1:00pm
room: Mila Auditorium 2
---

In this presentation, I will introduce some convergence results concerning the automatic differentiation of iterative algorithms, i.e., differentiating through the iterations, whether they are "smooth" or not. While the asymptotics of smooth problems are well understood (Gilbert 1992, Beck 1994), mainly thanks to the use of a fixed point theorem, the non-smooth case presents more difficulties. I will show how the framework of conservative Jacobians can achieve such results. I will also illustrate a strategy to adopt when the operator is not contracting, taking the differentiation of the Sinkhorn-Knopp algorithm as motivation. Finally, I will discuss one-shot differentiation, a method that combines the simplicity of automatic differentiation with the performance of implicit differentiation (in some cases). This approach, particularly suitable for fast algorithms, will be illustrated through superlinear optimization methods and bi-level optimization scenarios.

Work in collaboration with Jérôme Bolte (Toulouse School of Economics) and Edouard Pauwels (Toulouse School of Economics).