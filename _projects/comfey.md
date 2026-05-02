---
layout: page
title: Comfey
description: An agentic framework for triaging incidents in production cloud infrastructure
img: assets/img/publication_preview/xpert.jpg
importance: 2
category: research
related_publications: true
---

When production incidents occur in large-scale cloud systems, on-call engineers face a flood of alerts, telemetry, and runbooks. Triaging the root cause quickly is critical but demands deep system knowledge that is hard to encode in static rules.

**Comfey** is an agentic framework that automates incident triage. It uses LLM-powered agents that dynamically query telemetry data, consult historical incident records, and follow structured reasoning steps to identify likely root causes and surface actionable next steps for engineers.

Key contributions:
- An agent architecture that decomposes triage into sub-tasks (symptom analysis, hypothesis generation, evidence gathering)
- Integration with live production telemetry and incident history at Microsoft scale
- Evaluation against real incidents demonstrating improved triage accuracy and reduced time-to-mitigate

{% cite Comfey2026FSE %}

**Published at FSE '26 Industry Track.**
