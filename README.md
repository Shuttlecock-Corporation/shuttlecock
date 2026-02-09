# Shuttlecock

Shuttlecock is an open, community-driven compute runtime designed to make multiple GPUs behave like a single logical accelerator.

The project focuses on improving **effective compute utilization** by reducing software inefficiencies such as poor kernel scheduling, redundant memory movement, and rigid execution models.

Shuttlecock is not a GPU replacement. It is a runtime and execution layer that sits between applications and hardware.

---

## Problem Statement

Modern GPU workloads often underutilize available hardware due to:
- Fragmented execution models
- Excessive kernel launches
- Inefficient memory access patterns
- Manual tuning requirements
- Poor multi-GPU coordination

As a result, adding more GPUs frequently produces diminishing returns.

---

## What Shuttlecock Does

Shuttlecock provides:
- A **logical GPU abstraction** over one or more physical GPUs
- A kernel-centric execution model
- Runtime-driven scheduling and memory planning
- Backend support for CPU, CUDA, and ROCm targets

The goal is to maximize *useful work per GPU*, not raw theoretical performance.

---

## What Shuttlecock Is Not

- Not a CUDA replacement
- Not a deep learning framework
- Not a hardware project
- Not a general-purpose operating system

Shuttlecock focuses on a narrow, well-defined layer in the compute stack.

---

## Current Status

Shuttlecock is in early development.

Initial milestones:
- Define kernel interface
- Implement CPU backend
- Validate runtime architecture
- Add minimal CUDA support

Performance optimization will follow correctness.

---

## Who This Project Is For

- Systems programmers
- Compiler and runtime developers
- GPU and parallel computing enthusiasts
- Contributors interested in performance engineering

---

## Getting Involved

If you are interested in contributing:
- Read `MANIFESTO.md` for project principles
- Read `CONTRIBUTING.md` for contribution guidelines
- Check GitHub Issues for ownership opportunities

---

## License

License will be finalized before the first stable release.
