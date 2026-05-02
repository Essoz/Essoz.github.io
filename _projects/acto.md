---
layout: page
title: Acto
description: Automatic end-to-end testing for operation correctness of cloud system operators
img: assets/img/publication_preview/acto.jpg
importance: 5
category: research
related_publications: true
---

Cloud management platforms like Kubernetes rely on *operators* — programs that automate system operations using a state-reconciliation model. When an operator has a bug, it can silently leave managed systems in incorrect states, causing subtle and hard-to-diagnose failures in production.

**Acto** is the first automatic end-to-end testing framework for cloud system operators. It uses a state-centric approach: Acto continuously drives an operator to reconcile the managed system across a large state space, checking at each step whether the system correctly reaches the declared desired state.

Key contributions:
- State-transition modeling of operator behavior for systematic state-space exploration
- Automatic oracles that check correctness without requiring user-defined assertions
- Found 56 serious new bugs (42 confirmed, 30 fixed) across 11 Kubernetes operators

{% cite 10.1145/3600006.3613161 %}

**Published at SOSP '23.** Code available on [GitHub](https://github.com/xlab-uiuc/acto).
