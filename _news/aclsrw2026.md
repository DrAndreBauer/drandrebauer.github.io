---
layout: post
date: 2026-04-24 15:59:00-0400
inline: true
---

Our paper, "[Conformal LLM Routing with Distribution-Free Safety Guarantees](https://aclanthology.org/2026.acl-srw.70/)", has been accepted at the Student Research Workshop of the 64th Annual Meeting of the Association for Computational Linguistics ([ACL 2026](https://2026.aclweb.org)). We route queries between a cheaper and an expensive LLM using a conformal gate: a lightweight predictor trained on text embeddings, calibrated with Clopper-Pearson conformal prediction to guarantee that the violation rate among routed queries stays below a target tolerance. To our knowledge, this is the first input-based LLM router with distribution-free safety guarantees.