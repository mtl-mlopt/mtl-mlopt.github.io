---
author: Peter Richtarik
title: On Second Order Methods and Randomness
date: 2020-05-08 4:00pm
room: Virtual
paper: https://arxiv.org/abs/1912.01597
video: wXyXjTgINJI
---

We present two new remarkably simple stochastic second-order methods for minimizing the average of a very large number of sufficiently smooth and strongly convex functions. The first is a stochastic variant of Newton's method (SN), and the second is a stochastic variant of cubically regularized Newton's method (SCN). We establish local linear-quadratic convergence results. Unlike existing stochastic variants of second order methods, which require the evaluation of a large number of gradients and/or Hessians in each iteration to guarantee convergence, our methods do not have this shortcoming. For instance, the simplest variants of our methods in each iteration need to compute the gradient and Hessian of a {\em single} randomly selected function only. In contrast to most existing stochastic Newton and quasi-Newton methods, our approach guarantees local convergence faster than with first-order oracle and adapts to the problem's curvature. Interestingly, our method is not unbiased, so our theory provides new intuition for designing new stochastic methods.
