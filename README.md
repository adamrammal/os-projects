# Operating Systems Projects (xv6-riscv)

This repository is a hub for my Operating Systems coursework projects implemented on **xv6-riscv** (MIT’s Unix-like teaching OS).

References:
- xv6-riscv (MIT): https://github.com/mit-pdos/xv6-riscv
- xv6 book (RISC-V): https://pdos.csail.mit.edu/6.828/2023/xv6/book-riscv-rev3.pdf

---

## Projects

### OS Assignment 1 — System Calls & Process Utilities
Repo: https://github.com/adamrammal/os_assigment1  
Key work: `memsize` syscall + test, exit messages (`exit`/`wait`) + shell printing, `forkn` + `waitall` + `bigarray.c`.

### OS Assignment 2 — Synchronization (Peterson + Tournament Tree)
Repo: https://github.com/adamrammal/xv6-assignment2  
Key work: kernel-managed Peterson locks via syscalls (create/acquire/release/destroy), userspace tournament-tree mutual exclusion built using Peterson locks.

### OS Assignment 3 — Memory Management (Shared Memory + Logging)
Repo: https://github.com/adamrammal/os-assignment3  
Key work: shared-memory mapping/unmapping between processes + tests, multi-process logging using a shared buffer and atomic operations (CAS).

---

## Tech
C, xv6-riscv, processes, system calls, synchronization, virtual memory, shared memory, atomic operations.
