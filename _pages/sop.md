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

<!-- Slooo -->
With a focus on fail-slowness tolerance of quorum database systems, my first research project started remotely under the supervision of Prof. Tianyin Xu and Prof. Shuai Mu. As compared to fail-stop faults, common system implementations do not have decent tolerance against slow hardware (i.e. fail-slow) as shown by a few empirical stidies. To better understand root challenges in tackling fail-slow faults, I, collaborating with another undergraduate student, developed *Slooo*, a fault-injection testing framework for investigating system behavior under multiple kinds of fail-slow faults. It supports automatic testbed provisioning, role-based fault injection and system profiling. This tool has helped find fail-slow induced issues in popular databases such as MongoDB, RethinkDB, PolarDB and Etcd. It is used by *DepFast: Orchestrating Code of Quorum Systems (USENIX ATC'22)* to study fail-slow faults and UIUC CS598 as a part of course assignments. <!-- Impact of this research on myself --> The project has offered me three rewards. Despite major efforts were engineering, I, with little prior cs background, learned a lot about system design and implementation. I also learned how to push solid work effectively in a remote setting, which turned out to be useful for my later research experiences. <!-- Impact of this research on the community --> More importantly, the research let me understand the gap between people's expectation of an almighty system and reality of distributed systems. Inspired by the need for fault-tolerant computing services, I developed the idea of "City Brain as Distributed HPC Centers" and lead a team of 4 students to win the 2021 Internet+ competition (top 3 out of 142 teams). The idea proposes to build a network of wirelessly-interconnected containerized HPC clusters in a city, which provides computing power to compute-intensive and latency-sensitive applications, such as autonomous driving, smart city and cloud gaming. <!-- Unique advantage of this project, as compared to edge computing and centralized computing power --> The network can provide a more cost-effective and scalable solution than edge computing and centralized data centers while combining their advantages -- low latency and huge computing power. Fault-tolerant designs, which I learned during Slooo, and flexible deployment can further reduce the maintanence cost of the network. The project has been featured in the school news and considered by the local government as part of their smart city plans. Even though we didn't provide detailed technical feasibility analysis, seeing how my research can potentially push real world impacts keeps me excited and motivated to continue research in computer systems.

<!-- Acto -->

My next project: Acto - Automatic, Continuous Testing for Cloud Management Programs, extended my interest. <!-- Difficulty in testing control plane programs --> Supervised by Prof. Tianyin Xu and Prof. Owolabi Legunsen, we came up with an automatic testing tool for management programs in Kubernetes, namely operators. An operator, like an expert administrator, is responsible for full-lifecycle management of an application. Testing operators is important as they manage mission-critical applications, but has been hard due to XXX (scattered interface, indirect bug manifestation, etc.). ... TODOXXX a brief introduction on the design of Acto and its importance. So far, Acto has discovered 53 previous unkown bugs in 10 production-level operators, out of which 42 has been confirmed and 27 has been fixed. Specifically, my contributions include raising, refining and implementing the input exploration strategty that intentially test the operator's ability to recover from an erronous state, which has helped find XXX bugs (report the number of inspection). I also helped build features such as parallel testing which helps to reduce experiment time from days to hours. <!-- What about the decouplement and bug inspections? -->
Apart from the technical contributions, I helped mentored a remote undergraduate student who joined the project later, and was proud to have designed the academic poster for our tool and presented it in an internal event.
<!-- Going forward after acto? -->