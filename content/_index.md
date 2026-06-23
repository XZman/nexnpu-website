---
title: 'NexNPU'
date: 2026-05-26
type: landing

sections:
  - block: hero
    content:
      title: "NexNPU: Building an Open-Source Ecosystem<br>for Neural Processing Units"
      text: "13:30 – 17:00 EDT, June 27, 2026, Raleigh, NC, USA<br>Co-located with <a href=\"https://iscaconf.org/isca2026/\" target=\"_blank\" rel=\"noopener noreferrer\">ISCA 2026</a>"
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
        We first introduce the architecture and software stack of modern NPUs and highlight the missing pieces for an open NPU ecosystem. Then, we survey the open tool landscape for NPU development, including architectural design, compiler stack, system software, and hardware prototypes, discussing the capabilities and limitations of existing tools. To facilitate NPU architecture design, we will introduce NeuSim and discuss how users can utilize it to perform fast architectural design space exploration of NPU chips. Finally, we use Google TPU stack as a strong case study to demonstrate the importance of building the NPU ecosystem across the full stack. The tutorial concludes with perspectives on future research and community efforts toward an open, extensible, and production-relevant NPU ecosystem.

  - block: markdown
    id: schedule
    design:
      css_class: "schedule-section"
    content:
      title: Schedule
      text: |
        <p class="schedule-meta">13:30 – 17:00 <abbr title="Eastern Daylight Time (UTC-4)">EDT</abbr> · Room 302A</p>
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
                <td class="sched-time">13:30 – 13:40</td>
                <td class="sched-title">Opening: Why Do We Need an Open NPU Ecosystem?</td>
                <td class="sched-speaker">Jian Huang</td>
                <td class="sched-desc">Introduce the vision, scope, and roadmap of building an open NPU ecosystem.</td>
              </tr>
              <tr>
                <td class="sched-time">13:40 – 14:10</td>
                <td class="sched-title">The NPU Hardware and Software Stack: The Missing Pieces and Open Research Problems</td>
                <td class="sched-speaker">Yuqi Xue</td>
                <td class="sched-desc">Introduce the basic NPU hardware and software components and the differences from the GPU ecosystem, highlighting the missing pieces for NPU ecosystem and the open research problems.</td>
              </tr>
              <tr>
                <td class="sched-time">14:10 – 14:40</td>
                <td class="sched-title">Open Tools for NPU Development Lifecycle</td>
                <td class="sched-speaker">Yuqi Xue</td>
                <td class="sched-desc">Survey existing open tools across the NPU development lifecycle, including architectural design, compiler stack, system software, and hardware prototypes. Discuss the capabilities and limitations of existing tools and what remains to be done.</td>
              </tr>
              <tr>
                <td class="sched-time">14:40 – 15:30</td>
                <td class="sched-title">Architectural Design Space Exploration for NPUs: Methodology and Case Studies</td>
                <td class="sched-speaker">Yuqi Xue</td>
                <td class="sched-desc">Discuss the methodology/workflow for performing the architectural design space exploration for NPUs using the NeuSim simulator.</td>
              </tr>
              <tr class="sched-break">
                <td class="sched-time">15:30 – 16:00</td>
                <td class="sched-title"><svg class="coffee-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M17 8h1a4 4 0 1 1 0 8h-1"/><path d="M3 8h14v9a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z"/><line x1="6" y1="2" x2="6" y2="4"/><line x1="10" y1="2" x2="10" y2="4"/><line x1="14" y1="2" x2="14" y2="4"/></svg> <span class="sched-break-label">Coffee Break</span></td>
                <td class="sched-speaker"></td>
                <td class="sched-desc"></td>
              </tr>
              <tr>
                <td class="sched-time">16:00 – 16:45</td>
                <td class="sched-title">Demystifying the Google TPU Stack: From Silicon Architecture to Custom Pallas Kernels</td>
                <td class="sched-speaker">Srinath Mandalapu</td>
                <td class="sched-desc">Introduce the Google TPU stack as a case study for building NPU ecosystems.
                  <details class="talk-abstract">
                    <summary>Abstract</summary>
                    <div class="talk-abstract-body">
                      <p>Building an open and innovative NPU/TPU ecosystem requires developers to understand exactly how AI hardware executes code. This concise, 45-minute tutorial provides a fast-paced, bottom-up tour of the Google TPU computing stack.</p>
                      <p>We will break down the entire stack across three core layers:</p>
                      <ul>
                        <li><strong>The Hardware Layer:</strong> A look at the physical core architecture—Matrix Multiply Units (MXU), Vector Processing Units (VPU), and Vector Registers (VREGs)—and how DMA engines move data across HBM, VMEM, and SMEM using specific tiling and memory layouts.</li>
                        <li><strong>The Compiler Layer (XLA):</strong> Tracking the lifecycle of a program as it lowers from high-level JAX tracing down to JAXpr, StableHLO, and low-level optimization (LLO) into instruction-level VLIW bundles.</li>
                        <li><strong>The Scaling &amp; Customization Layer:</strong> Demystifying distributed execution by contrasting automatic JIT collectives with device-level explicit sharding (ShardMap), concluding with a practical introduction to writing custom hardware kernels using Pallas.</li>
                      </ul>
                      <p>By bridging the gap between silicon primitives and compiler abstractions, this talk equips developers with the mental models needed to build, optimize, and advocate for next-generation, open accelerator software stacks.</p>
                    </div>
                  </details>
                </td>
              </tr>
              <tr>
                <td class="sched-time">16:45 – 17:00</td>
                <td class="sched-title">Conclusion: Toward an End-to-End Open NPU Ecosystem</td>
                <td class="sched-speaker">Yuqi Xue</td>
                <td class="sched-desc">Summarize what we have and what are missing for an open NPU ecosystem and plans for future works.</td>
              </tr>
            </tbody>
          </table>
        </div>

  - block: markdown
    id: speakers
    design:
      css_class: "speakers-section bg-gray-50 dark:bg-gray-900"
    content:
      title: Speakers
      text: |
        <div class="speakers-grid not-prose">
          <div class="speaker-card">
            <h3>Yuqi Xue</h3>
            <p class="speaker-affiliation">University of Illinois Urbana-Champaign</p>
            <p class="speaker-bio">Yuqi Xue is a Ph.D. candidate at the University of Illinois Urbana-Champaign. He received his B.Sc. degree in computer engineering from the University of Illinois Urbana-Champaign. His research explores hardware/software co-design techniques for building efficient ecosystems for Neural Processing Units (NPUs). His research on NPUs has been published at top-tier conferences, including ISCA and MICRO, and has received MICRO Best Paper Runner-Up, MICRO Best Artifact Award, and IEEE Micro Top Picks. He also received Rambus Computer Engineering Fellowship, Dan Vivoli Endowed Fellowship, Qualcomm Graduate Award, and Yi-Min Wang and Pi-Yu Chung Research Award.</p>
          </div>
          <div class="speaker-card">
            <h3>Srinath Mandalapu</h3>
            <p class="speaker-affiliation">Google</p>
            <p class="speaker-bio">Srinath Mandalapu is a Senior Staff Engineer at Google specializing in the co-design of ML frameworks and TPU hardware. As a technical leader within Google's ML Frameworks organization, he serves as a primary architect for low-level Pallas kernels utilized in MaxText distributed training and vLLM TPU inference. His recent work focuses on the large-scale optimization of state-of-the-art open-source models—including DeepSeekV3, Llama, and Qwen—where he drives performance at the intersection of low-level hardware utilization (TPU/SparseCore) and high-level framework efficiency. Prior to Google, Srinath led distributed training and framework migrations (to PyTorch) at Meta and architected foundational advertising systems at Yahoo! that generated billions in annual revenue. He holds an M.S. in Computer Engineering from UC Santa Cruz and is an alumnus of the UC Berkeley Engineering Leadership Professional Program.</p>
          </div>
          <div class="speaker-card">
            <h3>Jian Huang</h3>
            <p class="speaker-affiliation">University of Illinois Urbana-Champaign</p>
            <p class="speaker-bio">Jian Huang is an Associate Professor and Y. T. Lo Faculty Fellow in the ECE department and an affiliated Associate Professor in Siebel School of Computing and Data Science at the University of Illinois at Urbana-Champaign. He received his Ph.D. in Computer Science at Georgia Institute of Technology in 2017. His research interests include computer systems and architecture, sustainable AI infrastructure, memory/storage systems, data systems, systems security, distributed systems, and especially the intersections of them. Most recently, he is working on sustainable AI infrastructures. His research contributions have been published at top-tier computer architecture and systems conferences such as ISCA, MICRO, ASPLOS, OSDI, and SOSP. His work received USENIX Best Paper Award, MICRO Best Paper Runner Up, MICRO Best Artifact award, multiple IEEE Micro Top Picks (and Honorable Mentions), and Microsoft Research Outstanding Project Award. He also received the inaugural SIGMICRO Early Career Award, NSF CAREER Award, NSF CRII Award, Dean's Award for Early Innovation, NetApp Faculty Fellowship Award, and Google Faculty Research Award. He is a member of MICRO Hall of Fame, and the founder of the Workshop on Hot Topics in System Infrastructure.</p>
          </div>
        </div>

  - block: markdown
    id: organizer
    design:
      css_class: "organizers-section"
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
    design:
      css_class: "resources-section bg-gray-50 dark:bg-gray-900"
    content:
      title: Tools & Resources

  - block: cta-button-list
    design:
      css_class: "resource-buttons bg-gray-50 dark:bg-gray-900"
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
