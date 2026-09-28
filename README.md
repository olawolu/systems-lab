# Systems Lab

Systems Lab is an academic, implementation-first study of computer systems. It is a working laboratory, not a notes repository: understanding is earned by implementing mechanisms by hand, testing their invariants, breaking them, and measuring what happens.

The curriculum is sequential:

1. Database internals
2. Networking
3. Operating systems
4. Distributed systems
5. Compilers and runtimes

The core learning loop for every topic is:

1. Read the minimum theory required.
2. Implement the mechanism.
3. Write tests for the core invariants.
4. Deliberately break the implementation.
5. Observe the failure modes.
6. Add instrumentation and benchmarks.
7. Compare the implementation with production or reference implementations.
8. Write a short technical retrospective covering design choices, failures, and production changes.

The target effort split is approximately 70% implementation, 20% books, papers, lectures, and source reading, and 10% experiments, benchmarking, and write-ups. Each phase is completed before moving to the next; the goal is depth, not simultaneous topic coverage.

The `curriculum/` directory contains the study plan. Implementations live in the corresponding topic directories. `notes/`, `papers/`, and `experiments/` are supporting material for the implementation work, not the primary output.

This repository intentionally starts without a framework, build system, CI, or language-specific tooling. Those choices should emerge from the work.
