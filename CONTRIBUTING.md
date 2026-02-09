# Shuttlecock Manifesto

## Purpose

Shuttlecock exists to improve real-world compute efficiency by addressing software-level inefficiencies in GPU programming and multi-GPU execution.

The project prioritizes practical outcomes over theoretical completeness.

---

## Core Principles

### 1. Efficiency Over Abstraction
Abstractions are only accepted if they improve clarity without hiding performance-critical behavior.

### 2. Correctness Before Performance
Optimizations are meaningless without correctness and reproducibility.

### 3. Narrow Scope, Deep Focus
Shuttlecock deliberately limits its scope to remain maintainable and effective.

### 4. Measurable Progress
Claims must be backed by benchmarks and observable results.

### 5. Vendor Neutrality
Shuttlecock does not optimize for a single hardware vendor at the expense of portability.

### 6. Community Ownership
Meaningful contributions earn long-term ownership and responsibility.

---

## Design Philosophy

- The runtime owns scheduling decisions
- The runtime owns memory planning
- Kernels express intent, not hardware strategy
- Specialization happens at runtime, not in user code

---

## Non-Goals

Shuttlecock explicitly avoids:
- Replacing existing ML frameworks
- Chasing benchmark-driven marketing
- Supporting every possible workload
- Vendor-specific lock-in strategies

---

## Governance

- Technical decisions are made based on merit and evidence
- Early development follows a BDFL (Benevolent Dictator for Life) model
- Maintainers are appointed based on sustained contributions
- All discussions must remain technical and respectful

---

## Success Criteria

Shuttlecock is successful if:
- It reduces multi-GPU complexity for developers
- It improves effective hardware utilization
- It enables contributors to learn and own real systems components
- It remains understandable and extensible over time

