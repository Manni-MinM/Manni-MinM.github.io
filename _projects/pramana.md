---
title: "Pramana"
description: "Real-world network datasets from real applications under diverse network conditions."
importance: 2
status: "active"
years: "2026 – present"
badge: "HotNets '26"
art: "pr"
img: "projects/pramana-fig1.png"
links:
  - label: "Paper"
    url: "https://arxiv.org/abs/2607.26352"
---

Pramana is a platform for building real-world network datasets. Instead of simulating traffic, it runs the actual applications (for example, a bulk BBR download competing with a Google Meet call) under controlled and diverse network conditions, and collects the resulting traffic and service-quality metrics.

![Pramana's thin waist: research intents (what) above, execution substrates (where) below, and the intent specification (how) at the waist](/images/projects/pramana-fig1.png)
*The thin waist, in three bands: research intents (what) above, execution substrates (where) below, and the intent specification (how) at the waist. From the HotNets 2026 paper.*
{: .pj-caption}

Under the hood, Pramana is shaped as a thin waist: research intents at the top, disparate execution substrates at the bottom.

Its single contract, the *intent specification*, splits an experiment into three independent axes: the **intent** (what data to generate), the **substrate** (where to generate it), and the **mechanism** (how to produce it). The same specification can then run on any substrate.

- We built a corpus of 255 data-generation intents mined from 66 published papers. The intent specification expresses all of them, while no existing tool supports more than 13%.
- Our proof-of-concept implementation already supports 34% of the intents, more than twice the best existing tool.

Pramana's artifacts include NetGent v2, a workflow-automation engine that generates realistic application traffic.

**Paper:** [Pramana: A Composable, Domain-Specific Backend for Empirical Networking Research](/publication/2026-pramana) (ACM HotNets 2026) · [arXiv:2607.26352](https://arxiv.org/abs/2607.26352)
