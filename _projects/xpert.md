---
layout: page
title: Xpert
description: Empowering incident management with query recommendations via large language models
img: assets/img/publication_preview/xpert.jpg
importance: 4
category: research
related_publications: true
---

When a production incident fires, engineers write domain-specific language (DSL) queries — like KQL for Azure Monitor — to sift through telemetry and pinpoint the problem. Crafting these queries is slow, error-prone, and demands expertise that varies across engineers.

**Xpert** automates KQL query recommendation for incident management. Starting from an empirical study of query usage patterns in a large-scale Microsoft cloud system, we built an end-to-end ML framework that leverages LLMs and historical incident data to generate tailored queries for new incidents.

Key contributions:
- Empirical study of KQL query usage across thousands of real production incidents
- Xpert framework: retrieval-augmented LLM pipeline for query generation
- Xcore: a novel metric for evaluating query quality across correctness, specificity, and efficiency
- Deployed in production at Microsoft, measurably reducing time-to-query for on-call engineers

{% cite 10.1145/3597503.3639081 %}

**Published at ICSE '24.**
