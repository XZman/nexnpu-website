---
title: 'NexNPU'
date: 2026-05-26
type: landing

sections:
  - block: hero
    content:
      title: "NexNPU: Building an [Open-Source] Ecosystem<br>for Neural Processing Units"
      text: "08:20 – 12:05 EDT, June 27, 2026, Raleigh, NC, USA<br>Co-located with <a href=\"https://iscaconf.org/isca2026/\" target=\"_blank\" rel=\"noopener noreferrer\">ISCA 2026</a>"
    design:
      layout: stacked
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "hero-wide"
      background:
        color: ""
        image:
          filename: ""
          filters:
            brightness: 0.5

  - block: markdown
    id: overview
    design:
      css_class: "overview-wide bg-gray-50 dark:bg-gray-900"
    content:
      title: Overview
      text: |
        To meet the exponential growth of AI, Neural Processing Units (NPUs) have become the cornerstone of modern computing infrastructure. The continued evolution of AI relies heavily on the advancement of NPUs, which demands collaborative efforts from both academia and industry. Currently, a gap exists between the exploration of new ideas in academia and the state-of-the-art implementation of industry. While academia continuously proposes novel systems and architectures, the lack of an open, industry-standard baseline limits the community's ability to validate and integrate these innovations into production-grade systems. We need an open-source NPU ecosystem for the community to innovate collaboratively across the entire stack.

        In this tutorial, we present a roadmap for building an open-source ecosystem for NPU design and implementation. We structure our discussion around three critical layers of the NPU stack – hardware architecture, compiler, and system infrastructure: (1) We establish a baseline open NPU architecture based on the state-of-the-art Google TPU architecture. We further extend the design with essential hardware support for modern deployment, such as advanced power management techniques (e.g., power gating, DVFS). (2) We introduce a tile-based programming interface and compiler optimizations designed to maximize hardware utilization and facilitate architecture/compiler co-design. (3) We examine the system infrastructure required for deploying NPUs at scale (e.g., in cloud environments), such as virtualization, resource allocation, and fleet-wide auto-scaling.

        Finally, to facilitate practical research and development within this ecosystem, we introduce NeuSim, an open-source NPU simulator framework. NeuSim models the performance and power characteristics of NPU chips as well as the fleet-wide allocation and scheduling behaviors for LLM serving workloads, enabling quick design space exploration across the hardware/software stack. We conclude by discussing AI-driven NPU Design, sharing our experiences on using LLMs for NPU design and implementation.

  - block: steps
    id: schedule
    content:
      title: Schedule
      text: "08:20 – 12:05 <abbr title=\"Eastern Daylight Time (UTC-4)\">EDT</abbr><br>Location: Room 302A"
      items:
        - date: "08:20 – 08:30"
          title: "Introduction: Towards Building an Open-Source NPU Ecosystem"
          text: ""
        - date: "08:30 – 09:00"
          title: "Open NPU Hardware Architecture"
          text: ""
        - date: "09:00 – 10:00"
          title: "Invited Talk (Speaker from Google)"
          text: ""
        - date: "10:00 – 10:30"
          title: "Coffee Break"
          text: ""
        - date: "10:30 – 11:00"
          title: "System Infrastructure for Deploying NPUs at Scale"
          text: ""
        - date: "11:00 – 11:30"
          title: "NeuSim: An Open-source Simulator Framework for NPUs (talk + demo)"
          text: ""
        - date: "11:30 – 12:00"
          title: "AI for NPU Design"
          text: ""
        - date: "12:00 – 12:05"
          title: "Closing Remark"
          text: ""
    design:
      layout: vertical
      marker_style: number
      numbering: decimal

  - block: markdown
    id: organizer
    design:
      css_class: "organizers-section bg-gray-50 dark:bg-gray-900"
    content:
      title: Organizers
      text: |
        <div class="organizers-grid not-prose">
          <div class="organizer-card">
            <img src="media/authors/yuqi-xue.png" alt="Yuqi Xue" class="organizer-photo">
            <div class="organizer-info">
              <h3><a href="https://yuqixue.com" target="_blank" rel="noopener">Yuqi Xue</a></h3>
              <p class="organizer-affiliation">University of Illinois Urbana-Champaign</p>
              <p class="organizer-email"><a href="mailto:yuqixue2@illinois.edu">yuqixue2@illinois.edu</a></p>
            </div>
          </div>
          <div class="organizer-card">
            <img src="media/authors/jian-huang.png" alt="Jian Huang" class="organizer-photo">
            <div class="organizer-info">
              <h3><a href="http://jianh.web.engr.illinois.edu/" target="_blank" rel="noopener">Jian Huang</a></h3>
              <p class="organizer-affiliation">University of Illinois Urbana-Champaign</p>
              <p class="organizer-email"><a href="mailto:jianh@illinois.edu">jianh@illinois.edu</a></p>
            </div>
          </div>
        </div>

  - block: markdown
    id: resources
    content:
      title: Resources

  - block: cta-button-list
    content:
      buttons:
        - text: Slides (TBD)
          url: "javascript:void(0)"
          icon: document-text
        - text: NeuSim — Open-Source NPU Simulator (TBD)
          url: "javascript:void(0)"
          icon: code-bracket
        - text: Paper (TBD)
          url: "javascript:void(0)"
          icon: book-open
        - text: GitHub (TBD)
          url: "javascript:void(0)"
          icon: code-bracket
---
