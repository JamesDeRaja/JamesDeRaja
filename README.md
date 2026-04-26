# James De Raja

## Senior Real-Time Performance Engineer

**Unity • Rendering • Frame Pacing • XR Optimization**

I build **deterministic performance systems** for real-time applications — focusing on stable frame delivery, GPU/CPU bottleneck isolation, and reproducible profiling workflows.

---

## What I Do

* Diagnose **CPU vs GPU bottlenecks** using profiler-backed experiments
* Design **controlled stress environments** to reproduce performance issues
* Optimize **rendering pipelines** for mobile and XR constraints
* Maintain **stable frame budgets (11ms / 16.6ms)** under load
* Build **telemetry-driven systems** to monitor runtime health

The goal is simple:
**consistent frame delivery under real-world stress — not just high FPS in ideal conditions.**

---

## Core Approach

Performance problems are not random.
They are measurable, reproducible, and isolatable.

My workflow:

* Establish baseline → apply controlled stress → measure delta
* Separate CPU vs GPU cost using profiler evidence
* Eliminate variance before applying optimizations
* Validate improvements with repeatable scenarios

**If it cannot be reproduced, it cannot be fixed reliably.**

---

## Featured Work

### XR Performance Lab

Deterministic stress framework for analyzing rendering cost in XR.

Focus areas:

* Stereo rendering overhead
* Overdraw amplification (200+ transparent layers)
* MSAA cost scaling
* Fragment workload vs submission cost

Key finding:

* Single rendering factor produced **+7ms GPU cost under stereo load** while CPU remained stable → clear GPU-bound scenario

🔗 [https://github.com/JamesDeRaja/XRPerformanceLab](https://github.com/JamesDeRaja/XRPerformanceLab)

---

### SoftMaskPro – UI Rendering Study

Performance breakdown of Unity UI masking under layered transparency.

Focus areas:

* Mask pass cost in UI pipelines
* Overdraw amplification in stacked elements
* Canvas rebuild CPU impact
* Tradeoffs between visual fidelity and performance

Result:

* Clear identification of **GPU-heavy UI scenarios caused by layered transparency and masking**

🔗 [https://github.com/JamesDeRaja/SoftMaskPro-Performance-Study](https://github.com/JamesDeRaja/SoftMaskPro-Performance-Study)

---

### ECS Performance Improvement Study

Comparison of update architectures under scale.

Variants:

* A — Per-object Update (baseline)
* B — Prefab-based Update
* C — Central Manager
* D — ECS (DOTS + Burst)

Focus areas:

* CPU scaling to 10,000+ entities
* GC elimination
* Update cost distribution
* Deterministic simulation control

Outcome:

* Measurable reduction in CPU overhead and improved scalability with ECS-based systems

🔗 [https://github.com/JamesDeRaja/ECS-Performance-Improvement](https://github.com/JamesDeRaja/ECS-Performance-Improvement)

---

## Engineering Philosophy

Performance is a systems problem.

* Define budgets in milliseconds, not FPS
* Measure before optimizing
* Remove non-determinism
* Validate under stress, not ideal conditions

**Architecture drives performance more than micro-optimizations.**

---

## Experience Snapshot

* 13+ years in real-time systems and Unity development
* Worked with publishers: Voodoo, Lion Studios, Supersonic
* Built and optimized systems for **hundreds of live game features**
* Improved retention and performance metrics through optimization-driven design

---

## Portfolio & Contact

🌐 [https://james.alphaden.club](https://james.alphaden.club)
🔗 [https://www.linkedin.com/in/james-de-raja/](https://www.linkedin.com/in/james-de-raja/)
