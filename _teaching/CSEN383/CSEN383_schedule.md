---
layout: archive
title: "CSEN 383: Schedule (Fall 2026)"
permalink: /teaching/CSEN383_schedule/
author_profile: false
---

{% include base_path %}

&nbsp; [Syllabus]({{ base_path }}/teaching/CSEN383_syllabus/) &nbsp;|&nbsp; **Schedule**

---

Subject to change. Camino is authoritative for any change announced in class.
Readings are due **before** the session they are listed under.
OSTEP = *Operating Systems: Three Easy Pieces*.

All labs are released on a Tuesday and due two weeks later, on a Tuesday.

## Week by week

| Week | Date | Topic | Reading | Due / exams |
|---|---|---|---|---|
| 1 | Tue, 9/22 | Introduction and OS organization | OSTEP 2 | |
| 1 | Thu, 9/24 | xv6, RISC-V, and the toolchain | xv6 book 1–2 | Group rosters due Fri Sep 25 · set up your dev environment |
| 2 | Tue, 9/29 | Processes, address spaces, the system call path | OSTEP 4–6 | **Lab 1 out** |
| 2 | Thu, 10/1 | Virtual memory I: paging, page tables, TLB | OSTEP 13, 15, 18 | |
| 3 | Tue, 10/6 | Virtual memory II: replacement, copy-on-write, mmap | OSTEP 19, 21, 22 · *PagedAttention* | |
| 3 | Thu, 10/8 | Kernel extensibility I: SPIN and Exokernel | *Exokernel* | **Quiz 1** — virtual memory |
| 4 | Tue, 10/13 | Kernel extensibility II: eBPF and the verifier | | **Lab 1 due** · demo 10/13–10/15 · **Lab 2 out** |
| 4 | Thu, 10/15 | Scheduling I: from FCFS to MLFQ | OSTEP 7, 8 | |
| 5 | Tue, 10/20 | Scheduling II: proportional share and sched_ext | OSTEP 9, 10 · *Lottery Scheduling* | **Quiz 2** — extensibility, eBPF |
| 5 | Thu, 10/22 | Synchronization | OSTEP 28, 30, 31 | |
| 6 | Tue, 10/27 | Deadlock and concurrency bugs · midterm review | OSTEP 32 | **Quiz 3** — scheduling · **Lab 2 due** · **Lab 3 out** |
| 6 | Thu, 10/29 | **MIDTERM 1** — in class, closed book | | Covers 9/22 through 10/22 |
| 7 | Tue, 11/3 | Multicore, NUMA, and CXL | *The Multikernel* | Lab 2 demo 11/3–11/5 |
| 7 | Thu, 11/5 | I/O, storage, and io_uring | OSTEP 36, 37, 44 | |
| 8 | Tue, 11/10 | File systems I: implementation and crash consistency | OSTEP 39–43 | **Quiz 4** — multicore, NUMA, I/O · **Lab 3 due** · demo 11/10–11/12 · **Lab 4 out** |
| 8 | Thu, 11/12 | File systems II: NFS, GFS, HDFS | OSTEP 48, 49 · *GFS* | |
| 9 | Tue, 11/17 | Virtualization and containers | OSTEP Appendix B | **Quiz 5** — file systems |
| 9 | Thu, 11/19 | Security and isolation: Spectre, Meltdown, TEEs | | |
| — | 11/23–27 | *Thanksgiving — no class* | | |
| 10 | Tue, 12/1 | Datacenter and disaggregated OS · final review | | **Quiz 6** — virtualization, security · **Lab 4 due** · demo 12/1--12/3 |
| 10 | Thu, 12/3 | **MIDTERM 2** — in class, closed book | | Emphasis on 10/27 onward |
| — | 12/7–12/9 | *Finals week — no activity* | |  |

<!-- ## Labs

| Lab | Topic | Out | Due | Demo |
|---|---|---|---|---|
| 1 | Environment setup; xv6 system calls | Tue Sep 29 | Tue Oct 13 | Oct 13–15 |
| 2 | xv6 scheduler: lottery and stride | Tue Oct 13 | Tue Oct 27 | Nov 3–5 |
| 3 | xv6 threads: `clone()` and a thread library | Tue Oct 27 | Tue Nov 10 | Nov 10–12 |
| 4 | A Linux CPU scheduler in BPF (sched_ext) | Tue Nov 10 | Tue Dec 1 | Dec 7–9 |

Useful advice: start the programming assignment early; do not leave it until the deadline. -->

## Papers

Five papers to read for the quarter. Each is due before the session listed, and each will be examined on a quiz alongside with the course slides.

| Read before | Paper |
|---|---|
| Tue Oct 6 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://arxiv.org/abs/2309.06180) (SOSP 2023) |
| Thu Oct 8 | [Exokernel: An Operating System Architecture for Application-Level Resource Management](https://pdos.csail.mit.edu/6.828/2008/readings/engler95exokernel.pdf) (SOSP 1995) |
| Tue Oct 20 | [Lottery Scheduling: Flexible Proportional-Share Resource Management](https://www.usenix.org/legacy/publications/library/proceedings/osdi/full_papers/waldspurger.pdf) (OSDI 1994) |
| Tue Nov 3 | [The Multikernel: A New OS Architecture for Scalable Multicore Systems](https://www.sigops.org/s/conferences/sosp/2009/papers/baumann-sosp09.pdf) (SOSP 2009) |
| Thu Nov 12 | [The Google File System](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf) (SOSP 2003) |
