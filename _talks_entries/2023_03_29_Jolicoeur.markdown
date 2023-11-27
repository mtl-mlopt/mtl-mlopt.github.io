---
author: Alexia Jolicoeur-Martineau
title: PopulAtion Parameter Averaging (PAPA)
date: 2023-03-29 1:30pm
room: Auditorium 1
---
Evolutionary Stochastic Gradient Descent (ESGD) is a method that alternates between parallel training of networks with SGD and an evolutionary process to improve the average fitness of the network’s population. ESGD allows one to improve neural network accuracy by not only scaling the network size but also the number of networks in the population. Although promising, ESGD is quite complex compared to traditional SGD training and requires massive computational resources (e.g., 128 GPUs on CIFAR-10) due to the large number of networks trained in parallel and many fitness evaluations; these aspect hinders its applicability to large datasets and limited compute.

In this work, we propose PopulAtion Parameter Averaging (PAPA): a simple method inspired by ESGD that performs similarly well (using only 5 models instead of 128 for ESGD) while requiring no fitness evaluation during training. We test PAPA on small populations of 2 to 10 models using a single GPU to test its applicability on small compute. We show that PAPA increases test accuracy significantly over baseline. We also demonstrate that more is not always better; increasing the size of the population is not always beneficial. Thus, maximum performance can often be achieved with a small population.
