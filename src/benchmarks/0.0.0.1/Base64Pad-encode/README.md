# Base64Pad-encode

This folder contains the encode benchmarks for the **Base64Pad** codec compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2 (22D49).

## Key Results

* encodes 1,000,000 bytes in **453.7 μs** using the **ByteLazy** pipeline

## Results Summary

| benchmark                      | duration |
| ------------------------------ | -------- |
| encode-1MB-Base64Pad-Text      | 523.3 μs |
| encode-1MB-Base64Pad-TextLazy  | 496.3 μs |
| encode-1MB-Base64Pad-TextShort | 512.7 μs |
| encode-1MB-Base64Pad-Byte      | 479.2 μs |
| encode-1MB-Base64Pad-ByteLazy  | 453.7 μs |
| encode-1MB-Base64Pad-ByteShort | 508.1 μs |

See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

| benchmark                         | nodes                      | current  | bound        |
| --------------------------------- | -------------------------- | -------- | ------------ |
| **encode-1MB-Base64Pad-ByteLazy** | **marvin** zaphod trillian | 453.7 μs | **485.0 μs** |
| encode-1MB-Base64Pad-ByteLazy     | dat                        | 453.7 μs | 352.0 μs     |

## Notes

The following observations concerning these results have been logged:

### [0.0.0.1]

#### Base64Pad-encode

* _lazy encode pipelines slightly better -- for now_ ([@cdornan], 2023-02-01)

    This should only be significant on small inputs.

    We hope to fix this soon in a coming release.

[Unreleased]: <https://github.com/cdornan/polymede-benchmarks>
[0.0.0.1]: <https://github.com/cdornan/polymede-benchmarks>
[@cdornan]: <https://github.com/cdornan>

[criterion.html](criterion.html)

