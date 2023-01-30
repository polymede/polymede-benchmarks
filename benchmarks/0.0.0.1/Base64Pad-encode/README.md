# Base64Pad-encode

This folder contains the encode benchmarks for the **Base64Pad** codec compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2 (22D49).

## Key Results

* encodes 1,000,000 bytes in **454.1 μs** using the **ByteLazy** pipeline


## Results Summary

| benchmark                      | duration |
| ------------------------------ | -------- |
| encode-1MB-Base64Pad-Text      | 525.2 μs |
| encode-1MB-Base64Pad-TextLazy  | 502.2 μs |
| encode-1MB-Base64Pad-TextShort | 511.3 μs |
| encode-1MB-Base64Pad-Byte      | 485.6 μs |
| encode-1MB-Base64Pad-ByteLazy  | 454.1 μs |
| encode-1MB-Base64Pad-ByteShort | 511.9 μs |


See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

| benchmark                         | nodes                      | current  | bound        |
| --------------------------------- | -------------------------- | -------- | ------------ |
| **encode-1MB-Base64Pad-ByteLazy** | **marvin** zaphod trillian | 454.1 μs | **485.0 μs** |
| encode-1MB-Base64Pad-ByteLazy     | dat                        | 454.1 μs | 352.0 μs     |

