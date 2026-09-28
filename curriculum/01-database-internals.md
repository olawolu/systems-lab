# 1. Database Internals

Approximate duration: 5 months

Primary language: C++

## Learning goals

- [ ] Understand how a database represents, stores, retrieves, and protects data.
- [ ] Explain the invariants behind each mechanism and the trade-offs made by production systems.

## Primary resources

- CMU 15-445/645 Database Systems
- Alex Petrov, *Database Internals*
- Martin Kleppmann, *Designing Data-Intensive Applications* (secondary/reference reading)

## Implementations

- [ ] Binary file layout
- [ ] Disk/page manager
- [ ] Page IDs and page allocation
- [ ] Slotted pages
- [ ] Tuples and record representation
- [ ] Buffer pool
- [ ] Continue the implementation sequence from the storage layer upward.

For every mechanism: define the invariants, implement it in C++, write focused tests, and document the public contract before extending it.

## Experiments

- [ ] Deliberately corrupt or violate each mechanism's assumptions and record the failure mode.
- [ ] Add instrumentation before benchmarking.
- [ ] Benchmark storage layout, allocation, page access, and buffer-pool behaviour.
- [ ] Compare results with a production or reference implementation.
- [ ] Write a short technical retrospective for each substantial implementation milestone.

## Papers

- TODO: collect foundational database papers and read only what is needed to guide the current implementation.

## Completion criteria

- [ ] Core mechanisms are implemented independently rather than copied from a framework.
- [ ] Core invariants have tests, including negative and failure-path tests.
- [ ] Failure injection, instrumentation, and benchmarks have been run and recorded.
- [ ] The implementation has been compared with a production or reference system.
- [ ] A retrospective explains design choices, observed failures, and what would change in production.
- [ ] The next phase is not started until this phase is complete.
