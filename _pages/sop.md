---
layout: SOP
title: Statement of Purpose
permalink: /
subtitle:
---

I want to brand myself as a slow starter but quick learner!!!!

This is super important!



<!-- Statement of Purpose -->
I want to push the development of next generation software system.
With the near end of moore's law, how can we build systems that can scale to future needs? How can we make computing power an invisible infrastructure for everyone? These questions, originated from my entrepreneurship and Microsoft Learn Student Ambassador experience, sparked my research interest which is further fostered by my time at UIUC SySNet and Microsoft Research Asia (MSRA). Specifically, my current research focuses on unearth and tackle issues of reliability, performance and security of cloud infrastructure and data-intensive systems. TODOXXX. It is with such reasons that I am determined to pursue a PhD degree.

<!-- Finding my research interest: -->
With a focus on fail-slowness tolerance of quorum database systems, my first research project started remotely under the supervision of Prof. Tianyin Xu and Prof. Shuai Mu. As compared to fail-stop faults, common system implementations do not have decent tolerance against slow hardware (i.e. fail-slow) as shown by a few empirical stidies. To better understand root challenges in tackling fail-slow faults, I, collaborating with another undergraduate student, developed *Slooo*, a fault-injection testing framework for investigating system behavior under multiple kinds of fail-slow faults. It supports automatic testbed provisioning, role-based fault injection and system profiling. This tool has helped find fail-slow induced issues in popular databases such as MongoDB, RethinkDB, PolarDB and Etcd. It is used by *DepFast: Orchestrating Code of Quorum Systems (USENIX ATC'22)* to study fail-slow faults and adopted by UIUC CS598 as a part of course assignments. <!--- Impact of this research on myself ---> Though this project required mainly engineering effort, the experience gained me significant amount of (generic and database-specific) knowledge as a student with little prior CS background. In addition, this project also educated me about the gap between real situtation and people's expection in software systems: I was both astonished and excited -- astonished because previously I thought software systems should be almightly once they are given good amount of hardware; excited because the gap reveals the potential huge impact of doing system research <!--- Simply put -- triggered my passion --->.



<!-- The tool, as a sub-project of DepFast: Orchestrating Code of Quorum Systems, is adopted later as part of the course assignment of UIUC CS598. With this tool, we easily evaluated a few popular distributed database and found performance bugs in them in various settings. Though I was pretty happy with being engaged in the technical aspects of open-ended questions, which gained me significant technical skills as a non-computer science student, I wished to contribute more to the ideas as well. I wanted to gain insight and produce ideas that would really push the boundaries of the field.
<!-- Put this paragraph in the outcome section of slooo -->
I realized my passion in computer . In the first few semester, I was not able explore my interest and develop skillsets in computer science due to limited course offering during COVID-19. Luckily enough, through few courses in computer architecture, I find myself enjoying understanding and building complex systems and attempted to expand my interest in software systems.

<!-- Acto -->
<!-- https://middleware.io/blog/kubernetes-challenges-and-solutions/ -->
The prevalence of cloud systems has made it possible for developers to build and deploy applications without worrying about the underlying infrastructure. However, the complexity of cloud systems has also made it difficult for developers to understand and debug their applications. In this project, we aim to tackle the correctness issues in cloud computing management systems.
We set out to explore an automatic solution to correctness control plane softwares (operators). Correctness of operators has been critical yet hard to guarantee as bugs only manifest indirectly in the application the operator manages. Prior to prevalence of large-scale intent-based cluster orchestration platforms like Kubernetes, reasoning operator correctness is hard due to the scattered interface, nasty corner cases, application observability issues and oracle generation, etc. Fortunately, a unified API interface that comes with the recent emergence of large-scale intent-based orchestration platforms has created, for the first time ever, an opportunity to create a generic testing software for control-plane softwares. Benefiting from the intent-based nature, Acto’s oracle compares the user-specified state with the actual system state retrieved from the API interface and reports alarms on inconsistencies. Acto can explore the input space exhaustively but efficiently by generating structurally-correct input with the input schema that comes with all operators. Acto performs static program analysis against the operator source code and automatically reasons about the field dependencies and mappings between input state and output state, thus generating input more efficiently and reducing false alarms caused by naively compare input and system states. I was proud to have designed the academic poster for Acto and presented it in an UIUC internal event. Benefiting from my previous remote work experience, I was able to effectively onboard and collaborate with students remotely. So far, Acto has discovered 50+ previously unknown bugs in ten production-level operators, and among them 30+ are fixed after we reported them. This work has also led to an ongoing OSDI’23 submission.

<!-- Equal Access and Outreach in STEM -->
As a first generation student from a low-income family, there was no one to turn to help when it comes to life decisions and career plan. 
<!-- Beginning
 - Motivation
    - connect research work with real world impact
 - Current 


Finding My research interest
 - Acto

 - MSRA

 - Slooo

Teaching and Leadership Experience
I want to do research because of the potential impact. First inspired from:
 - Entrepreneurship
 - Microsoft Learn Student Ambassador
 - Unimate
I want to grew up to be a person out of that

Future Work & Where I see myself. -->
-  -->