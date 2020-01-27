---
title: "Method of Testing Shared Caches/TLB Intervention"
date: 2015-04-03
pubtype: "Publication"
featured: true
description: "A method for testing coherency in shared caches and TLB subsystem with true sharing as the underlying stress mechanism."
tags: ["Multicore", "Stress", "Coherency", "Shared Memory", "Cache", "Microprocessor", "TLB", "Irritator", "Verification"]
link: "https://priorart.ip.com/IPCOM/000241210"
fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 400
sitemap:
  priority : 0.8
---

A validation test environment for testing shared cache and TLB intervention using true sharing of a set of address buckets, where each bucket contains a fixed number of memory addresses, in order to stimulate cache coherence and memory consistency logic, is presented. Tests are run from a main microprocessor(s) and use a loop based algorithm. Each address bucket is treated as a single entity and uses its own reader’s-writer lock to allow concurrent access. For creating additional stress, special instruction(s) called irritators are thrown around each bucket access randomly. The irritators include instructions that directly or indirectly modify cache line states (e.g., cache and TLB management instructions).
