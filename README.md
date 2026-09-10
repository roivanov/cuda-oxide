# CUDA Rust

This repository contains the CUDA Rust workspace:

- [`cuda-oxide/`](cuda-oxide/) — SIMT compiler, device runtime, book, and examples
- [`cutile-rs/`](cutile-rs/) — tile DSL and compiler

Host crates (`cuda-bindings`, `cuda-core`, `cuda-async`) are published from
cutile-rs and consumed from crates.io. The workspace manifest remains at the
repository root. See [`cuda-oxide/README.md`](cuda-oxide/README.md) for the SIMT
project overview.
