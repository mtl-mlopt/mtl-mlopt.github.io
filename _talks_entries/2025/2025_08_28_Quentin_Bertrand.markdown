---
author: Quentin Bertrand
title: "On the Closed-Form of Flow Matching: Generalization Does Not Arise from Target Stochasticity"
date: 2025-08-28 1:00pm
room: Mila Auditorium 1
---

Modern deep generative models can now produce high-quality synthetic samples that are often indistinguishable from real training data. A growing body of research aims to understand why recent methods – such as diffusion and flow matching techniques – generalize so effectively. Among the proposed explanations are the inductive biases of deep learning architectures and the stochastic nature of the conditional flow matching loss. In this work, we rule out the latter – the noisy nature of the loss – as a primary contributor to generalization in flow matching. First, we empirically show that in high-dimensional settings, the stochastic and closed-form versions of the flow matching loss yield nearly equivalent losses. Then, using state-of-the-art flow matching models on standard image datasets, we demonstrate that both variants achieve comparable statistical performance, with the surprising observation that using the closed-form can even improve performance.