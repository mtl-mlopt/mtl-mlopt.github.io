---
author: Motahareh Sohrabi
title: Weight-Sharing Regularization
date: 2024-03-06 1:30pm
paper: [https://arxiv.org/abs/2311.03096]
room: Microsoft Research Labs
---

Weight-sharing is ubiquitous in deep learning. Motivated by this, we introduce “weight-sharing regularization” for neural networks, defined as R(w) = sum_i>j |wi − wj |. We study the proximal mapping of R and provide an intuitive interpretation of it in terms of a physical system of interacting particles. Using this interpretation, we desig a novel parallel algorithm for proxR which provides an exponential speedup over previous algorithms, with a depth of O(log3 d). Our algorithm makes it feasible to train weight-sharing regularized deep neural networks with proximal gradient descent. Experiments reveal that weight-sharing regularization enables fully-connected networks to learn convolution-like filters