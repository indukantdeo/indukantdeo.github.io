---
layout: page
title: Differentiable Acoustic Ray Tracing (DART)
description: A JAX solver for underwater sound propagation, environmental sensitivity, and inversion.
importance: 1
category: Research and industry
---

DART uses acoustic rays and Gaussian beams to model underwater sound propagation in two and three dimensions. It is implemented in JAX and runs on a GPU.

Differentiating the solver shows how predicted transmission loss responds to changes in sound speed and seabed geometry. These gradients can be used to identify which parts of the environment most affect a receiver and to estimate environmental parameters from acoustic measurements in inverse problems.
