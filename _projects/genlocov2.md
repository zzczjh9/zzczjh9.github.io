---
layout: project
title: "GenlocoV2: Transformer-based Generalized Locomotion Controller"
date: 2025-06-01
image: /assets/img/g1_512.gif
alt_text: "Multi-robot locomotion training"
project_url: https://github.com/zzczjh9/genlocov2
github_repo: zzczjh9/genlocov2
summary: "Transformer-based generalized locomotion controller for morphology & topology-agnostic policy learning"
category: research
importance: 1
---

## Overview

GenlocoV2 is a Transformer-based generalized locomotion controller designed for morphology & topology-agnostic policy learning across diverse robotic embodiments including quadrupeds, bipeds, and humanoids.

<div style="text-align: center;">
<img src="/assets/img/g1_512.gif" alt="GenlocoV2 Demo" style="width: 50%; height: auto;">
</div>
*Multi-robot training demonstration showing diverse robot morphologies learning locomotion*


- **Multi-robot Training Pipeline**: Implemented procedurally generated morphological and topological variations across distinct robot types with randomized link sizes, masses, and joint configurations
- **Novel Robot Representation**: Designed graph-based joint descriptions with positional embeddings incorporating joint relative positions
- **Offline Training Framework**: Developed framework combining Behavior Cloning (BC) distillation and DAgger with expert trajectory relabeling
