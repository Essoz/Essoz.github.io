---
layout: page
title: TrainCheck
description: Catching silent errors in deep learning training with automated proactive checks
img: assets/img/publication_preview/traincheck-logo.png
importance: 1
category: research
related_publications: true
---

Deep learning training is notoriously opaque: runs can silently diverge due to numerical issues, misconfigured hyperparameters, or subtle framework bugs — and the only signal is a bad loss curve discovered hours or days later.

**TrainCheck** addresses this by automatically synthesizing and injecting *proactive checks* into the training loop. These checks encode invariants derived from mathematical properties of optimization algorithms and neural network architectures, flagging violations at runtime without requiring users to write specifications.

Key contributions:
- A taxonomy of silent error patterns in DL training (numerical, semantic, configuration)
- An automated framework that generates and inserts checks derived from training invariants
- Evaluation on real-world training bugs across PyTorch workloads, catching errors that standard logging misses

{% cite MLSilentBug2025OSDI %}

**Published at OSDI '25.** Code available on [GitHub](https://github.com/OrderLab/TrainCheck).
