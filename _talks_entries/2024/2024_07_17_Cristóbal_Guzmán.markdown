---
author: Cristóbal Guzmán
title: "The Role of Sparsity on Differentially Private Learning"
date: 2024-07-17 1:30pm
room: Mila Auditorium 2
---

With the increasing use of personally sensitive data in machine learning applications, privacy has become a central concern. In this context, differential privacy (DP) offers a rigorous and quantifiable control of the privacy risk of a machine learning model. One of the main problems of interest in differential privacy is stochastic optimization, where we are interested in computing a model that approximately minimizes the empirical or population excess risk, while satisfying differential privacy with respect to the data used for training the model.

In this talk, we will present various settings where one can obtain nearly dimension independent accuracy rates in differentially private (stochastic) optimization and saddle-point problems. We start with results involving stochastic optimization under polyhedral constraints, popular in sparsity-oriented machine learning. Next, we move to stochastic saddle-point problems, where we study the use of stochastic mirror-descent methods and vertex sampling. Finally, I will present results on a "dual" counterpart of the above problems: stochastic optimization with sparse gradients, a setting of high relevance in large embedding models. Here, we provide new matching upper and lower bounds both in the convex and nonconvex settings.