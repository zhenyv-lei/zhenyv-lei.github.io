---
title:          "SuriVPP: A High-Performance Virtualized Intrusion Prevention System"
date:           2021-11-1 00:00:00 +0800
selected:       false
pub:            " Core Member | <strong>1st Place</strong>, National Undergraduate Extracurricular Sci&Tech Competition"

# pub_date:       "Jul 2021 - Nov 2021"
pub_pre:        <span class="badge badge-pill badge-publication badge-success">High-Performance Systems </span>
pub_post:       <span class="badge badge-pill badge-publication">Jul 2021 - Nov 2021</span>

abstract: >-
  1) Engineered SuriVPP, a high-performance IPS coupling Suricata with Vector Packet Processing (VPP) to resolve kernel-user context switch bottlenecks, enabling high-speed user-space packet processing on ARM/x86 platforms.<br/>
  2) Developed a custom zero-copy VPP plugin that embeds the Suricata engine directly into the VPP thread, eliminating inter-process communication overhead; re-engineered memory management using lock-free ring buffers and CPU affinity to maximize cache locality.<br/>
  3) Achieved 3× native performance (6 Gbps) with ultra-low latency (19.89 µs, ~22% of the national standard) on Kunpeng servers, verifying the system's stability via Dockerized cross-platform deployment.<br/>
cover:          /assets/images/covers/2021-SuriVPP A High-Performance Virtualized Intrusion Prevention System.svg
authors:
  - Zhenyu Lei
  - ...
  - Advised by Prof. Sanfeng Zhang

links:
  # Code: https://github.com/luost26/bubble-visual-hash
  # Demo: https://luost26.github.io/bubble-visual-hash
---
