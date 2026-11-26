---
layout: project
img: assets/img/projects/dart-transmission-loss.png
img_alt: "Transmission loss field with two circular seamount outlines in the horizontal plane"
img_caption: "DART’s full three-dimensional transmission-loss field for the double-seamount benchmark at 100 Hz and 400 m depth."
title: Differentiable Acoustic Ray Tracing (DART)
description: A JAX solver for underwater sound propagation, environmental sensitivity, and inversion.
importance: 1
category: Research and industry
---

DART uses acoustic rays and Gaussian beams to model underwater sound propagation in two and three dimensions. It is implemented in JAX and runs on a GPU.

Differentiating the solver shows how predicted transmission loss responds to changes in sound speed and seabed geometry. These gradients can be used to identify which parts of the environment most affect a receiver and to estimate environmental parameters from acoustic measurements in inverse problems.
