---
title: 'NexNPU'
date: 2026-05-26
type: landing

sections:
  - block: hero
    content:
      title: "NexNPU: Building an Open-Source Ecosystem<br>for Neural Processing Units"
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

        In this tutorial, we will present a roadmap for building an open-source ecosystem for NPU design and implementation, including the hardware architecture, compiler, and system infrastructure. Based on this roadmap, we will first establish a baseline NPU hardware architecture based on the state-of-the-art Google TPU architecture. Then, we introduce NeuSim, an open-source NPU simulator framework that models the performance and power characteristics at chip-level and fleet-level, and demonstrate the research enabled by NeuSim. We also feature an invited talk from Google about the XLA compiler for TPUs.

  - block: steps
    id: schedule
    content:
      title: Schedule
      text: "08:20 – 12:05 <abbr title=\"Eastern Daylight Time (UTC-4)\">EDT</abbr><br>Location: Room 302A"
      items:
        - date: "08:30 – 08:40"
          title: "Introduction: Towards Building an Open-Source NPU Ecosystem"
          text: ""
        - date: "08:40 – 09:00"
          title: "Open NPU Hardware Architecture"
          text: ""
        - date: "09:00 – 10:00"
          title: "Invited Talk on XLA (Speaker from Google)"
          text: ""
        - date: "10:00 – 10:30"
          title: "Coffee Break"
          text: ""
        - date: "10:30 – 11:00"
          title: "NeuSim: An Open-Source Simulator Framework for NPUs"
          text: ""
        - date: "11:00 – 11:30"
          title: "Building an Energy-Efficient NPU Chip"
          text: ""
        - date: "11:30 – 12:00"
          title: "System Infrastructure for NPU Fleet"
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
        - text: "NeuSim — Open-Source NPU Simulator (GitHub)"
          url: "https://github.com/platformxlab/NeuSim"
          icon: code-bracket
        - text: "V10: Hardware-Assisted NPU Multi-tenancy (ISCA '23)"
          url: "https://dl.acm.org/doi/10.1145/3579371.3589059"
          icon: book-open
        - text: "Neu10: Hardware-Assisted Virtualization of NPUs (MICRO '24)"
          url: "https://arxiv.org/abs/2408.04104"
          icon: book-open
        - text: "ReGate: Enabling Power Gating in NPUs (MICRO '25)"
          url: "https://dl.acm.org/doi/10.1145/3725843.3756038"
          icon: book-open
---
