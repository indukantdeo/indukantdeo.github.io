---
layout: project
img: assets/img/projects/wave-forecasting-architecture.png
img_alt: "Wave fields are encoded into a latent space, advanced in time, and decoded back to the original space"
img_caption: "The wave-forecasting model encodes the wave field, advances the latent state in time, and decodes the predicted field."
img_source: https://arxiv.org/abs/2504.11433
title: Physics-guided wave forecasting
description: Deep learning models for forecasting the evolution of wave fields over long time horizons.
importance: 2
category: PhD research
---

I used convolutional autoencoders to compress wave fields into a low-dimensional representation and recurrent networks to advance that representation in time. I extended this approach with attention inspired by multistep time integration and a physics-based loss that separates components of the prediction error.

[Journal of Computational Physics article](https://doi.org/10.1016/j.jcp.2026.115333) · [Physics of Fluids article](https://doi.org/10.1063/5.0086926)
