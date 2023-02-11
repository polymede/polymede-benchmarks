# Base64Pad

This folder contains the benchmark results for the Base64Pad compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2 (22D49).

## Key Results

* encodes 1,000,000 bytes in **452.6 μs** using the **ByteLazy** pipeline
* decodes to 1,000,000 bytes in **1.893 ms** using the **ByteLazy** pipeline

## Results Summary

| benchmark                       | duration |
| ------------------------------- | -------- |
| encode-1MB-Base64Pad-Text       | 526.6 μs |
| encode-1MB-Base64Pad-TextLazy   | 498.9 μs |
| encode-1MB-Base64Pad-TextShort  | 507.2 μs |
| encode-1MB-Base64Pad-Byte       | 481.0 μs |
| encode-1MB-Base64Pad-ByteLazy   | 452.6 μs |
| encode-1MB-Base64Pad-ByteShort  | 512.2 μs |
| encode-1MB-N#Base64Pad-Byte     | 451.6 μs |
| encode-1MB-N#Base64Pad-ByteLazy | 451.4 μs |
| encode-1MB-X#Base64Pad-Byte     | 479.4 μs |
| encode-1MB-X#Base64Pad-ByteLazy | 451.7 μs |
| decode-1MB-Base64Pad-Text       | 1.916 ms |
| decode-1MB-Base64Pad-TextLazy   | 1.926 ms |
| decode-1MB-Base64Pad-TextShort  | 1.938 ms |
| decode-1MB-Base64Pad-Byte       | 1.896 ms |
| decode-1MB-Base64Pad-ByteLazy   | 1.893 ms |
| decode-1MB-Base64Pad-ByteShort  | 1.951 ms |
| decode-1MB-N#Base64Pad-Byte     | 1.893 ms |
| decode-1MB-N#Base64Pad-ByteLazy | 1.892 ms |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

| benchmark                         | nodes      | current  | bound        |
| --------------------------------- | ---------- | -------- | ------------ |
| **encode-1MB-Base64Pad-ByteLazy** | **marvin** | 452.6 μs | **485.0 μs** |
| encode-1MB-Base64Pad-ByteLazy     | zaphod     | 452.6 μs | 352.0 μs     |

## Notes

The following observations concerning these results have been logged:

### [Unreleased]

#### Base64Pad-decode

* _decode times appear to be somewhat greater than expected_ ([@cdornan], 2023-02-01)

    This needs further investigation.

### [0.0.0.1]

#### Base64Pad-encode

* _lazy encode pipelines slightly better -- for now_ ([@cdornan], 2023-02-01)

    We hope to fix this soon in a coming release.

[Unreleased]: <https://github.com/cdornan/polymede-benchmarks>
[0.0.0.1]: <https://github.com/cdornan/polymede-benchmarks>
[@cdornan]: <https://github.com/cdornan>

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base64Pad-decode]
* [Base64Pad-encode]
* [Base64Pad-misc]

[Base64Pad-encode]: <./Base64Pad-encode/index.html>
[Base64Pad-misc]: <./Base64Pad-misc/index.html>
[Base64Pad-decode]: <./Base64Pad-decode/index.html>

