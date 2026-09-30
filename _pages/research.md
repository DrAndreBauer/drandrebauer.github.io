---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 2
---

My research makes the infrastructure behind modern AI efficient, predictable, and trustworthy. I study how real systems behave, from container platforms and microservices to LLM-based applications, by measuring and benchmarking them, and I combine these insights with forecasting and machine learning to build systems that behave reliably in terms of cost, latency, and correctness.

### Efficient AI and Cloud Infrastructure

AI and data-intensive workloads increasingly run on shared container platforms whose behavior is hard to predict and expensive to over-provision. My work analyzes and optimizes these platforms. This includes proactive and hybrid auto-scaling mechanisms that plan resources ahead of workload changes, a large-scale study of what determines container start-up times, and a systematic evaluation of Kubernetes for GenAI inference pipelines, from automatic speech recognition to LLM summarization. I also develop open datasets and scheduling strategies for function-as-a-service and multi-site computing.

__Selected papers:__
[Chameleon (TPDS 2018)](https://ieeexplore.ieee.org/document/8465991) ·
[Chamulteon (ICDCS 2019)](https://ieeexplore.ieee.org/document/8885153) ·
[Production-Ready Autoscaling (ICPE 2022)](https://dl.acm.org/doi/10.1145/3489525.3511680) ·
[Container Start Times (CCGrid 2023)](https://ieeexplore.ieee.org/document/10171550) ·
[Globus Compute Dataset (FGCS 2024)](https://doi.org/10.1016/j.future.2023.12.007) ·
[Multi-Site Scheduling (IPDPS 2024)](https://ieeexplore.ieee.org/document/10596467) ·
[Kubernetes for GenAI Inference (ICPE 2026)](https://doi.org/10.1145/3777884.3796983)

### Reliable AI with Guarantees

LLMs are powerful but unpredictable, which limits their use in settings where errors are costly. I develop methods that make LLM-based systems dependable without giving up their efficiency. Examples are routing queries between cheap and expensive models while keeping the error rate below a target, profiling and repairing faulty layers for fault-tolerant transformer inference, and structured inference pipelines with explicit validation and abstention for high-stakes applications.

__Selected papers:__
[Conformal LLM Routing (ACL SRW 2026)](https://aclanthology.org/2026.acl-srw.70/) ·
[Routing to Interpretable Surrogates (arXiv 2026)](https://arxiv.org/abs/2603.14623) ·
Linear Layer Repair (BlackboxNLP 2026) ·
[Structured LLM Inference (ECML PKDD 2026)](https://doi.org/10.1007/978-3-032-37654-1_31) ·
[Retrieval and Citation Augmented Generation (AIxDKE 2026)](https://doi.org/10.1109/AIXDKE67294.2026.00008)

### Performance Prediction and Observability

Modern microservice applications constantly adapt through auto-scaling, load balancing, and failure recovery, which makes their performance hard to understand and predict. My work captures not only steady-state but also transient behavior, makes monitoring data queryable together with the system's architecture, and investigates how the design of LLM-based workflows, such as decomposing tasks, affects root cause analysis.

__Selected papers:__
[Transient Phases of Microservices (MASCOTS 2025)](https://doi.org/10.1109/MASCOTS67699.2025.11283322) ·
[Simulated and Synthetic Microservice Applications (SSP 2025)](https://dl.gi.de/handle/20.500.12116/47943) ·
graphobs (ECSA 2026) ·
Task Decomposition in LLM-Based Root Cause Analysis (SSP 2026)

### Time Series Analysis and Forecasting

Time series forecasting is the foundation of much of my work: it turns monitoring data into decisions, such as when to scale a system. I have developed automated hybrid forecasting methods, a standardized benchmark for comparing forecasting methods, and, more recently, a modular view of the forecasting pipeline that separates representation, information extraction, and projection.

__Selected papers:__
[Time Series Forecasting for Self-Aware Systems (Proceedings of the IEEE 2020)](https://ieeexplore.ieee.org/document/9069193) ·
[Telescope (ICDE 2020)](https://ieeexplore.ieee.org/document/9101575) ·
[Libra Forecasting Benchmark (ICPE 2021)](https://dl.acm.org/doi/10.1145/3427921.3450241) ·
[Decomposing the Forecasting Pipeline (IJCNN 2026)](https://arxiv.org/abs/2507.05891)

### Interdisciplinary Collaborations

I apply my expertise in time series analysis and machine learning together with clinical partners in cardiac surgery, for example to detect acute kidney injury early and to predict atrial fibrillation after surgery.

__Selected papers:__
[Acute Kidney Injury Detection (EJCTS 2022)](https://academic.oup.com/ejcts/article-abstract/62/5/ezac289/6581706) ·
[Interatrial Block and Atrial Fibrillation (JTCVS Open 2024)](https://doi.org/10.1016/j.xjon.2024.10.003) ·
[Atrial Fibrillation Prediction (Frontiers in Cardiovascular Medicine 2026)](https://doi.org/10.3389/fcvm.2026.1886483)

### Community

I founded and chair the [SPEC RG Predictive Data Analytics Working Group](https://research.spec.org/working-groups/rg-predictive-data-analytics/), and several of my tools, such as the Libra forecasting benchmark and the TeaStore microservice benchmark, have been reviewed and published by the Standard Performance Evaluation Corporation (SPEC).

The full list of papers is on the [publications page]({{ '/publications/' | relative_url }}).
