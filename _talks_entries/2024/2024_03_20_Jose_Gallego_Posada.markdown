---
author: Jose Gallego-Posada
title: On PI controllers for updating Lagrange multipliers in constrained optimization
date: 2024-03-20 1:30pm
paper: [TBD]
room: Microsoft Research Labs
---

Constrained optimization offers a powerful framework to prescribe desired behaviours in neural network models. Typically, constrained problems are solved via their min-max Lagrangian formulations, which exhibit unstable oscillatory dynamics when optimized using gradient descent-ascent. The adoption of constrained optimization techniques in the machine learning community is currently limited by the lack of reliable, general-purpose update schemes for the Lagrange multipliers. This paper provides an optimization perspective on Lagrange multiplier updates based on PI controllers, extending the work of Stooke et al. (2020). We provide theoretical and empirical insights explaining the inability of momentum methods to address the shortcomings of gradient descent-ascent, and contrast this with the success of our proposed vPI controller. Our experiments demonstrate that vPI reliably stabilizes the multiplier dynamics and its hyperparameters enjoy robust and predictable behavior.