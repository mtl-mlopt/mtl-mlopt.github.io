---
author: Aaron Mishkin
title: "Level Set Teleportation: An Optimization Perspective"
date: 2025-02-10 1:00pm
room: Mila Auditorium 2
---

We study level set teleportation, an optimization routine which tries to accelerate gradient descent (GD) by maximizing the gradient norm over a level set of the objective. While teleportation intuitively speeds-up GD via bigger steps, current work lacks convergence theory for convex functions, guarantees for solving the teleportation operator, and even clear empirical evidence showing this acceleration. We resolve these open questions. For convex functions satisfying Hessian stability, we prove that GD with teleportation obtains a combined sub-linear/linear convergence rate which is strictly faster than GD when the optimality gap is small. This is in sharp contrast to the standard (strongly) convex setting, where teleportation neither improves nor worsens convergence. To evaluate teleportation in practice, we develop a projected-gradient method requiring only Hessian-vector products. We use this to show that gradient methods with access to a teleportation oracle out-perform their standard versions on a variety of problems. We also find that GD with teleportation is faster than truncated Newton methods, particularly for non-convex optimization.