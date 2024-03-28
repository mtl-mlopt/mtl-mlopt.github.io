---
author: Adam Oberman
title: Theoretical insights into self-supervised feature representation learning.
date: 2024-04-03 1:00pm
room: Microsoft Research Labs
---

Adam Oberman is a McGill mathematics Professor and CIFAR AI chair on sabbatical at Mila this year. He teaches two Machine Learning classes, including one on generalization and stability theory.
In this theory-oriented talk aimed at a general audience, I will present recent work by a number of authors who have developed a theory for how deep neural network learn features from data augmentation. Despite using data without labels, these features are effective for downstream classification tasks: in fact, they achieve the same accuracy as supervised models, using only a fraction of the labels.
My interest is in understanding if how this phenomena can give insight into feature representation learning in general: how do we train a network to learn features useful for downstream tasks?
I'll present some background material on generalization theory, and the stability approach to generalization, which is very compatible with convex optimization.
Then I'll present recent work that shows that many SLL algorithms correspond to minimizing the same loss for features. This loss is a generalization of a functional PCA type loss.
Using this loss along with the appropriate stability/generalization theory, we can then show that linear classifiers using these can learn classifiers.