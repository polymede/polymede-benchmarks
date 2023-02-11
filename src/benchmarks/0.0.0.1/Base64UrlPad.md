# Base64UrlPad

This folder contains the benchmark results for the Base64UrlPad compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2 (22D49).

## Key Results

* encodes 1,000,000 bytes in **451.7 μs** using the **ByteLazy** pipeline
* decodes to 1,000,000 bytes in **1.901 ms** using the **ByteLazy** pipeline

## Results Summary

| benchmark                          | duration |
| ---------------------------------- | -------- |
| encode-1MB-Base64UrlPad-Text       | 528.6 μs |
| encode-1MB-Base64UrlPad-TextLazy   | 496.5 μs |
| encode-1MB-Base64UrlPad-TextShort  | 511.6 μs |
| encode-1MB-Base64UrlPad-Byte       | 480.9 μs |
| encode-1MB-Base64UrlPad-ByteLazy   | 451.7 μs |
| encode-1MB-Base64UrlPad-ByteShort  | 512.2 μs |
| encode-1MB-N#Base64UrlPad-Byte     | 451.9 μs |
| encode-1MB-N#Base64UrlPad-ByteLazy | 452.8 μs |
| encode-1MB-X#Base64UrlPad-Byte     | 479.8 μs |
| encode-1MB-X#Base64UrlPad-ByteLazy | 452.1 μs |
| decode-1MB-Base64UrlPad-Text       | 1.929 ms |
| decode-1MB-Base64UrlPad-TextLazy   | 1.930 ms |
| decode-1MB-Base64UrlPad-TextShort  | 1.954 ms |
| decode-1MB-Base64UrlPad-Byte       | 1.911 ms |
| decode-1MB-Base64UrlPad-ByteLazy   | 1.901 ms |
| decode-1MB-Base64UrlPad-ByteShort  | 1.961 ms |
| decode-1MB-N#Base64UrlPad-Byte     | 1.898 ms |
| decode-1MB-N#Base64UrlPad-ByteLazy | 1.897 ms |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

| benchmark                            | nodes      | current  | bound        |
| ------------------------------------ | ---------- | -------- | ------------ |
| **encode-1MB-Base64UrlPad-ByteLazy** | **marvin** | 451.7 μs | **485.0 μs** |
| encode-1MB-Base64UrlPad-ByteLazy     | zaphod     | 451.7 μs | 352.0 μs     |

## Notes

The following observations concerning these results have been logged:

### [Unreleased]

#### Base64UrlPad-decode

* _decode times appear to be somewhat greater than expected_ ([@cdornan], 2023-02-01)

    This needs further investigation.

### [0.0.0.1]

#### Base64UrlPad-encode

* _lazy encode pipelines slightly better -- for now_ ([@cdornan], 2023-02-01)

    We hope to fix this soon in a coming release.

[Unreleased]: <https://github.com/cdornan/polymede-benchmarks>
[0.0.0.1]: <https://github.com/cdornan/polymede-benchmarks>
[@cdornan]: <https://github.com/cdornan>

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base64UrlPad-decode]
* [Base64UrlPad-encode]
* [Base64UrlPad-misc]

[Base64UrlPad-misc]: <./Base64UrlPad-misc/index.html>
[Base64UrlPad-encode]: <./Base64UrlPad-encode/index.html>
[Base64UrlPad-decode]: <./Base64UrlPad-decode/index.html>

