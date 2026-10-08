# CDAIP — Compiler-Driven AI Processor

**Exploring compiler-driven hardware/software co-design for efficient AI computing.**

## Overview

CDAIP (Compiler-Driven AI Processor) is an exploratory project focused on
the co-design of AI processors and their compiler infrastructure.

Modern embedded processors increasingly integrate heterogeneous computing
resources, such as CPUs, DSPs, NPUs, DMA engines, and specialized memory
subsystems.

While these components can provide significant computational capabilities,
achieving high end-to-end performance remains challenging.

Optimizing individual kernels or processing engines does not necessarily
result in optimal system-level performance. Data movement, memory
constraints, synchronization, and interactions between hardware resources
can become major performance bottlenecks.

CDAIP explores how a compiler can reason about the processor as a whole,
rather than treating its computing resources as independent components.

## Motivation

This project is motivated by challenges encountered when optimizing machine
learning workloads for resource-constrained microcontrollers.

Many embedded processors expose specialized hardware capabilities that
could potentially be exploited more effectively through compiler-driven
optimization.

The central idea behind CDAIP is to investigate how hardware architecture
and compiler design can evolve together to improve overall workload
performance.

## Research Interests

CDAIP aims to explore several interconnected topics:

- Heterogeneous processor architectures
- Compiler and hardware/software co-design
- MLIR-based compilation
- Workload mapping across heterogeneous compute resources
- Memory-aware optimization and data movement
- Computation and communication overlap
- Global resource scheduling
- Hardware-aware autotuning
- Roofline-based performance analysis

The exact architecture, compiler design, and implementation approach
are still being explored.

## Long-Term Vision

The long-term goal is to investigate a heterogeneous AI processor and
compiler framework in which computation, memory management, and data
movement are optimized together.

Rather than maximizing the performance of individual processing engines,
CDAIP seeks to understand how compiler-driven optimization can bring
complete AI workloads closer to the attainable performance limits of
the underlying hardware.

## Project Status

🚧 **Early Exploration**

CDAIP is currently in its initial research and design phase.

The architecture, compiler infrastructure, simulation methodology,
and development roadmap have not yet been finalized.

This repository will evolve as design decisions are made and initial
experiments are implemented.

## Related Technologies

Technologies and frameworks being considered include:

- [MLIR](https://mlir.llvm.org/)
- [LLVM](https://llvm.org/)
- [IREE](https://iree.dev/)
- [RISC-V](https://riscv.org/)
- [Verilator](https://verilator.org/)

These are areas of exploration, not finalized technology choices.

---

**CDAIP — Compiler-Driven AI Processor**

*Exploring the boundaries of compiler-driven optimization and
heterogeneous AI processor design.*
