---
linkTitle: Documentation
title: Introduction
---

To meet the exponential growth of AI, Neural Processing Units (NPUs) have become the cornerstone of modern computing infrastructure. The continued evolution of AI relies heavily on the advancement of NPUs, which demands collaborative efforts from both academia and industry. Currently, a gap exists between the exploration of new ideas in academia and the state-of-the-art implementation of industry. While academia continuously proposes novel systems and architectures, the lack of an open, industry-standard baseline limits the community's ability to validate and integrate these innovations into production-grade systems. We need an open-source NPU ecosystem for the community to innovate collaboratively across the entire stack.

<!--more-->

In this tutorial, we present a roadmap for building an open-source ecosystem for NPU design and implementation. We structure our discussion around three critical layers of the NPU stack – hardware architecture, compiler, and system infrastructure: (1) We establish a baseline open NPU architecture based on the state-of-the-art Google TPU architecture. We further extend the design with essential hardware support for modern deployment, such as advanced power management techniques (e.g., power gating, DVFS). (2) We introduce a tile-based programming interface and compiler optimizations designed to maximize hardware utilization and facilitate architecture/compiler co-design. (3) We examine the system infrastructure required for deploying NPUs at scale (e.g., in cloud environments), such as virtualization, resource allocation, and fleet-wide auto-scaling.

Finally, to facilitate practical research and development within this ecosystem, we introduce NeuSim, an open-source NPU simulator framework. NeuSim models the performance and power characteristics of NPU chips as well as the fleet-wide allocation and scheduling behaviors for LLM serving workloads, enabling quick design space exploration across the hardware/software stack. We conclude by discussing AI-driven NPU Design, sharing our experiences on using LLMs for NPU design and implementation.

## Next

{{< cards >}}
  {{< card url="getting-started" title="Get Started" icon="document-text" subtitle="Create your docs in just 5 minutes!" >}}
{{< /cards >}}
