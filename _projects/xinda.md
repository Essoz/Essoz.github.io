---
layout: page
title: Xinda
description: Understanding and enhancing slow-fault tolerance in modern distributed systems
img: assets/img/publication_preview/slow-faults.png
importance: 3
category: research
related_publications: true
---

Distributed systems are routinely tested for crash faults, but *slow faults* — nodes that respond correctly but unusually slowly — are far harder to handle. Existing timeout-based defenses are brittle: too aggressive and they cause false positives; too lenient and they let slow nodes stall entire operations.

**Xinda** is a study and toolkit for characterizing and improving slow-fault tolerance. We conducted a systematic study of how 10 widely-used distributed systems handle slow faults, revealing that one-size-fits-all timeout strategies consistently fail. Xinda then provides adaptive mechanisms that tune fault-tolerance behavior based on runtime signals.

Key contributions:
- First large-scale empirical study of slow-fault handling across production distributed systems
- Characterization of failure modes specific to slow faults vs. crash faults
- Adaptive slow-fault tolerance mechanisms that outperform static timeout policies

{% cite SlowFaultStudy2025NSDI %}

**Published at NSDI '25.** Code available on [GitHub](https://github.com/OrderLab/xinda).
