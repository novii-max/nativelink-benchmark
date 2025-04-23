# Nativelink Benchmarks

This repo provides per-commit benchmarking for the [Nativelink](https://github.com/TraceMachina/nativelink) project using Bazel.

## What It Does

- Benchmarks Nativelink builds with:
  - ✅ Remote cache only
  - ✅ Remote cache + remote execution

## Files Included

- `scripts/benchmark.sh`: Main benchmark script
- `configs/benchmark.bazelrc`: Bazel config for benchmarking
- `README.md`: You are here :)

## Usage

1. Clone this repo
2. Run the benchmark script:
   ```bash
   ./scripts/benchmark.sh
