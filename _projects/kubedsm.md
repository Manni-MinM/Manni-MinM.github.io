---
title: "KubeDSM"
description: "Kubernetes scheduling and live migration for cloud-assisted edge clusters."
importance: 3
years: "2025"
badge: "Cluster Comput."
art: "kd"
img: "projects/kubedsm-fig2.png"
links:
  - label: "Paper"
    url: "https://arxiv.org/abs/2501.07130"
---

KubeDSM is a Kubernetes-based framework for dynamic scheduling and migration in cloud-assisted edge clusters. It schedules in batches to reduce resource fragmentation, and it uses live migration (intra-edge, edge-to-cloud, and cloud-to-edge) to keep latency-sensitive workloads at the edge whenever capacity allows.

![KubeDSM component diagram](/images/projects/kubedsm-fig2.png)
*KubeDSM's components: the scheduler core (immediate scheduler and suggester), the event handler, and the placement manager, which talk to the Kubernetes API server. From the Cluster Computing paper.*
{: .pj-caption}

- Paper: [Cluster Computing, 2026](/publication/2026-kubedsm) · [arXiv:2501.07130](https://arxiv.org/abs/2501.07130)
