# Awesome NUMA with stars

A community-oriented list of libraries, tools, and resources aimed to assist with NUMA-aware software development.

[Non-Uniform Memory Access (NUMA)](https://en.wikipedia.org/wiki/Non-uniform_memory_access) refers to multiprocessor systems whose memory is divided into multiple memory nodes.

## Contributing

To add, remove or change things on the list:
[please submit a pull request to the GitHub repository](https://github.com/domargan/awesome-numa) ⭐ 78 | 🐛 1 | 📅 2026-05-12.

## NUMA library bindings and interfaces

* [hwloc](https://github.com/open-mpi/hwloc) ⭐ 731 | 🐛 148 | 🌐 C | 📅 2026-08-18 - A portable API to detect and exploit the topology of parallel architectures
* [libnuma](https://github.com/numactl/numactl) ⭐ 505 | 🐛 16 | 🌐 C | 📅 2026-08-03 - The libnuma shared library to control NUMA policy for processes or shared memory on Linux
  * [py-numa](https://github.com/smira/py-numa) ⭐ 28 | 🐛 3 | 🌐 Python | 📅 2019-11-05 - Python bindings for libnuma
  * [go-numa](https://github.com/rakyll/go-numa) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2019-11-18 - Go bindings for libnuma
  * [jnuma](https://github.com/xerial/jnuma) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2013-03-13 - Java bindings for libnuma
  * [ocaml-numa](https://github.com/stevebleazard/ocaml-numa) ⭐ 3 | 🐛 0 | 🌐 OCaml | 📅 2018-03-04 - OCAML bindings for libnuma
  * [numa-rs](https://github.com/cwpearson/numa-rs) ⭐ 0 | 🐛 2 | 🌐 Rust | 📅 2018-05-17 - Rust bindings for libnuma
* [libNumaAPI](https://github.com/sergeyvfx/libNumaAPI) ⚠️ Archived - A cross-platform API wrapper for NUMA architecture
* [Windows NUMA API](https://docs.microsoft.com/en-us/windows/win32/procthread/numa-support) - Official Microsoft Win32 NUMA API

## NUMA-aware memory placement and scheduling

* [numactl](https://github.com/numactl/numactl) ⭐ 505 | 🐛 16 | 🌐 C | 📅 2026-08-03 - A program to run other programs with a specific NUMA policy

* [Umpire](https://github.com/LLNL/Umpire) ⭐ 418 | 🐛 35 | 🌐 C++ | 📅 2026-08-13 - An application-focused API for memory management on NUMA & GPU architectures

* [RAM Coffers](https://github.com/Scottcjn/ram-coffers) ⭐ 160 | 🐛 10 | 🌐 Python | 📅 2026-08-16 - NUMA-aware weight banking for LLM inference on IBM POWER8, routing model weights to cognitive-function-mapped NUMA nodes with prefetch hints

* [Tesson](https://github.com/kobolog/tesson) ⭐ 84 | 🐛 0 | 🌐 Go | 📅 2018-01-10 -  A tool for NUMA-aware sharding with Docker

* [libtorque](https://github.com/dankamongmen/libtorque) ⭐ 76 | 🐛 1 | 🌐 C | 📅 2021-05-19 - A threaded, continuations-based I/O event library for manycore NUMA machines

* [golang-numa](https://github.com/lrita/numa) ⭐ 40 | 🐛 1 | 🌐 Go | 📅 2024-10-31 - A golang utility library for NUMA-aware code

* [numanji](https://github.com/bastion-rs/numanji) ⭐ 30 | 🐛 4 | 🌐 Rust | 📅 2021-04-29 - A rustlang Local-affinity first NUMA-aware allocator with optional fallback

* [pgasus](https://github.com/osmhpi/pgasus) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2021-08-26 - A C++ parallel programming framework for NUMA systems, based on PGAS semantics

* [NumaAllocator](https://github.com/ReidAtcheson/numaallocator) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2016-09-21 - A simple C++ header NUMA memory allocator

* [NUMASK](https://github.com/sss-lehigh/numask) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2020-08-21 - A skip list designed to exploit the characteristics of NUMA architectures to improve performance

* [numatool](https://github.com/go2starr/numatool) ⚠️ Archived - A wrapper to linux kernels `move_pages` system call to balance processes' pages across NUMA nodes

* [memkind](https://memkind.github.io/memkind/) - A heap manager which enables control of memory characteristics and a partitioning of the heap between kinds of memory

## Observation and profiling tools

* [pcm-numa](https://github.com/opcm/pcm) ⭐ 3,316 | 🐛 69 | 🌐 C++ | 📅 2026-08-11- A tool to monitor local and remote memory accesses on a NUMA system
* [numastat](https://github.com/numactl/numactl) ⭐ 505 | 🐛 16 | 🌐 C | 📅 2026-08-03 - A program display NUMA allocation statistics
* [NumaTOP](https://github.com/intel/numatop) ⭐ 212 | 🐛 15 | 🌐 C | 📅 2025-12-03 - An observation tool for runtime memory locality characterization and analysis of processes and threads running on a NUMA system
* [irqstat](https://github.com/lanceshelton/irqstat) ⭐ 68 | 🐛 1 | 🌐 Python | 📅 2021-04-16 - A `/proc/interrupts` watcher designed for NUMA systems
* [NUMAPROF](https://github.com/memtt/numaprof) ⭐ 55 | 🐛 25 | 🌐 C++ | 📅 2026-06-30 - A NUMA memory profliler based on Pintool to track remote memory accesses
* [NumaMMA](https://github.com/numamma/numamma) ⭐ 32 | 🐛 4 | 🌐 C | 📅 2025-06-10 - A lightweight NUMA memory profiler/analyzer and a NUMA application execution engin
* [Numalize](https://github.com/matthiasdiener/numalize) ⭐ 21 | 🐛 2 | 🌐 R | 📅 2019-02-07 - A memory tracing tool to detect communication and page usage of NUMA applications
* [numap](https://github.com/numap-library/numap) ⭐ 21 | 🐛 1 | 🌐 C | 📅 2024-05-27 - A Linux library for memory profiling based on hardware performance monitoring unit
* [Numa-Trace](https://github.com/marksfu/Numa-Trace) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2012-04-23 - A Pin tool to track NUMA memory accesses
* [SnuMAP](https://github.com/SnuMAP/SnuMAP) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2025-07-22 - A NUMA performance profiler
* [NUMACC](https://github.com/mJace/numacc) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2019-08-14 - A golang-based tool to check CPU affinity and NUMA configuration for containers and pods

## Benchmarking

* [Comm|Scope](https://github.com/c3sr/comm_scope) ⭐ 28 | 🐛 14 | 🌐 C++ | 📅 2023-10-26 - A NUMA-aware multi-CPU multi-GPU CUDA data transfer benchmarks
* [numa-bench](https://github.com/stephentu/numa-bench) ⭐ 13 | 🐛 0 | 🌐 C++ | 📅 2015-02-03 - A NUMA-aware memory allocation benchmark
* [nurdma](https://github.com/sss-lehigh/nurdma) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2019-05-18 - Understanding RDMA behavior in NUMA systems
* [Numafac](https://github.com/matthiasdiener/numafac) ⭐ 2 | 🐛 0 | 🌐 Groff | 📅 2016-11-11 - Scripts to calculate the NUMA factor of NUMA machines, based on the stream and lmbench3 benchmarks
* [numabench](https://github.com/BrownBigData/numabench) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2014-10-07 - A NUMA benchmarking tool

## NUMA-aware data structures

* [rw-numa-locks](https://github.com/azu-labs/rw-numa-locks) ⭐ 19 | 🐛 0 | 🌐 C | 📅 2014-06-12 - A NUMA-aware reader-writer locks
* [Skyhooks](https://github.com/ShisoftResearch/Skyhooks) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2019-12-16 - An experimental NUMA-aware, lock-free heap memory allocator
* [NUMA\_Black-Box](https://github.com/xqgex/NUMA_Black-Box) ⭐ 9 | 🐛 1 | 🌐 C | 📅 2017-09-04 - Black-box concurrent data structures for NUMA architectures

## About

This list was compiled by [Domagoj Margan](https://github.com/domargan) with help and resources from the systems community.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
