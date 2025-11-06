---
author: Juan Ramirez
title: "Feasible Learning"
date: 2025-11-19 1:00pm
room: Mila Auditorium 2 and online: https://umontreal.zoom.us/j/83867040431?pwd=qdwMH1gMt0srY8QOMqoejXoZIM4Yuv.1
---

We introduce Feasible Learning (FL), a sample-centric learning paradigm where models are trained by solving a feasibility problem that bounds the loss for each training sample. In contrast to the ubiquitous Empirical Risk Minimization (ERM) framework, which optimizes for average performance, FL demands satisfactory performance on every individual data point. Since any model that meets the prescribed performance threshold is a valid FL solution, the choice of optimization algorithm and its dynamics play a crucial role in shaping the properties of the resulting solutions. In particular, we study a primal-dual approach which dynamically re-weights the importance of each sample during training. To address the challenge of setting a meaningful threshold in practice, we introduce a relaxation of FL that incorporates slack variables of minimal norm. Our empirical analysis, spanning image classification, age regression, and preference optimization in large language models, demonstrates that models trained via FL can learn from data while displaying improved tail behavior compared to ERM, with only a marginal impact on average performance.

Juan Ramirez is a PhD candidate at Mila and the University of Montreal, supervised by Simon Lacoste-Julien. He works on constrained learning—developing scalable algorithms that enforce requirements such as fairness, sparsity, and safety in neural networks via Lagrangian methods. He develops Cooper, an open-source PyTorch library for constrained learning, and co-organized the NeurIPS 2025 Workshop on Constrained Learning.