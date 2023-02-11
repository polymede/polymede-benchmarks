# Base64Pad-encode

This folder contains the encode benchmarks for the **Base64Pad** codec compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2 (22D49).

## Key Results

* encodes 1,000,000 bytes in **452.6 μs** using the **ByteLazy** pipeline

## Results Summary

| benchmark                      | duration |
| ------------------------------ | -------- |
| encode-1MB-Base64Pad-Text      | 526.6 μs |
| encode-1MB-Base64Pad-TextLazy  | 498.9 μs |
| encode-1MB-Base64Pad-TextShort | 507.2 μs |
| encode-1MB-Base64Pad-Byte      | 481.0 μs |
| encode-1MB-Base64Pad-ByteLazy  | 452.6 μs |
| encode-1MB-Base64Pad-ByteShort | 512.2 μs |

See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

| benchmark                         | nodes      | current  | bound        |
| --------------------------------- | ---------- | -------- | ------------ |
| **encode-1MB-Base64Pad-ByteLazy** | **marvin** | 452.6 μs | **485.0 μs** |
| encode-1MB-Base64Pad-ByteLazy     | zaphod     | 452.6 μs | 352.0 μs     |

## Notes

The following observations concerning these results have been logged:

### [0.0.0.1]

#### Base64Pad-encode

* _lazy encode pipelines slightly better -- for now_ ([@cdornan], 2023-02-01)

    We hope to fix this soon in a coming release.

[Unreleased]: <https://github.com/cdornan/polymede-benchmarks>
[0.0.0.1]: <https://github.com/cdornan/polymede-benchmarks>
[@cdornan]: <https://github.com/cdornan>

[criterion.html](criterion.html)

