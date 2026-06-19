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

        In this tutorial, we will present a roadmap for building an open-source ecosystem for NPU design and implementation.
        We first introduce the architecture and software stack of modern NPUs, highlighting key design principles and open research challenges. We will introduce NeuSim, an open-source NPU simulation framework for modeling the performance and power characteristics of NPU chips as well as the fleet-wide allocation and scheduling behaviors for LLM serving workloads, enabling quick design space exploration across the hardware/software stack. The tutorial concludes with perspectives on future research and community efforts toward an open, extensible, and production-relevant NPU ecosystem.

  - block: markdown
    id: schedule
    design:
      css_class: "schedule-section"
    content:
      title: Schedule
      text: |
        <p class="schedule-meta">13:30 – 17:10 <abbr title="Eastern Daylight Time (UTC-4)">EDT</abbr> · Room 302A</p>
        <div class="schedule-table-wrap not-prose">
          <table class="schedule-table">
            <thead>
              <tr>
                <th class="col-time">Time</th>
                <th class="col-title">Title</th>
                <th class="col-speaker">Speaker</th>
                <th class="col-desc">Description</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="sched-time">13:30 – 13:50</td>
                <td class="sched-title">Opening</td>
                <td class="sched-speaker">Jian Huang</td>
                <td class="sched-desc">Introduce the vision and roadmap of building an open NPU ecosystem.</td>
              </tr>
              <tr>
                <td class="sched-time">13:50 – 14:30</td>
                <td class="sched-title">NPU Architecture</td>
                <td class="sched-speaker">Yuqi Xue</td>
                <td class="sched-desc">Introduce the hardware architecture and software stack for NPUs, and the open research problems for the NPU stack.</td>
              </tr>
              <tr>
                <td class="sched-time">14:30 – 15:30</td>
                <td class="sched-title">NeuSim: An Open-Source Simulator Framework for NPUs</td>
                <td class="sched-speaker">Yuqi Xue</td>
                <td class="sched-desc">Introduce our NPU simulator framework, including the design, workflow, demo, and example researches done with NeuSim.</td>
              </tr>
              <tr class="sched-break">
                <td class="sched-time">15:30 – 16:00</td>
                <td class="sched-title"><svg class="coffee-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M17 8h1a4 4 0 1 1 0 8h-1"/><path d="M3 8h14v9a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z"/><line x1="6" y1="2" x2="6" y2="4"/><line x1="10" y1="2" x2="10" y2="4"/><line x1="14" y1="2" x2="14" y2="4"/></svg> <span class="sched-break-label">Coffee Break</span></td>
                <td class="sched-speaker"></td>
                <td class="sched-desc"></td>
              </tr>
              <tr>
                <td class="sched-time">16:00 – 17:00</td>
                <td class="sched-title">Keynote Talk on Google TPU Stack</td>
                <td class="sched-speaker"><a href="https://www.linkedin.com/in/1vaibhavsingh">Vaibhav Singh (Google)</a></td>
                <td class="sched-desc">TBD</td>
              </tr>
              <tr>
                <td class="sched-time">17:00 – 17:10</td>
                <td class="sched-title">Conclusion</td>
                <td class="sched-speaker">Yuqi Xue</td>
                <td class="sched-desc">Closing remark, and the future work toward an open NPU ecosystem.</td>
              </tr>
            </tbody>
          </table>
        </div>

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
    design:
      css_class: "resource-buttons"
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
