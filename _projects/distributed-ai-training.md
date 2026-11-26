---
layout: project
img: assets/img/projects/distributed-training-overlap.png
img_alt: "Simulated compute and communication overlap versus distance for two GPT-3 model sizes"
img_caption: "Simulated compute–communication overlap as the distance between data centers increases, for 13B- and 175B-parameter GPT-3 models."
img_source: https://arxiv.org/abs/2605.19169
title: Network performance in distributed AI training
description: Discrete-event simulation of how optical fiber latency affects training across data centers.
importance: 2
category: Research and industry
---

At Corning, we used discrete-event simulation to study how network latency affects data-parallel training across geographically separated data centers. We compared standard single-mode fiber and hollow-core fiber to see how their propagation delays affect the amount of GPU computation that overlaps with communication.

[ECOC 2026 paper](https://doi.org/10.1364/ECEOC.2026.Th1_G1) · [Open preprint](https://arxiv.org/abs/2605.19169)
