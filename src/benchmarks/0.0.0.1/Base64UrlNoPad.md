# Base64UrlNoPad

This folder contains the benchmark results for the Base64UrlNoPad compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2 (22D49).

## Key Results

* encodes 1,000,000 bytes in **452.0 μs** using the **ByteLazy** pipeline
* decodes to 1,000,000 bytes in **1.932 ms** using the **ByteLazy** pipeline

## Results Summary

| benchmark                           | duration |
| ----------------------------------- | -------- |
| encode-1MB-Base64UrlNoPad-Text      | 524.4 μs |
| encode-1MB-Base64UrlNoPad-TextLazy  | 497.4 μs |
| encode-1MB-Base64UrlNoPad-TextShort | 513.7 μs |
| encode-1MB-Base64UrlNoPad-Byte      | 479.9 μs |
| encode-1MB-Base64UrlNoPad-ByteLazy  | 452.0 μs |
| encode-1MB-Base64UrlNoPad-ByteShort | 509.3 μs |
| decode-1MB-Base64UrlNoPad-Text      | 1.926 ms |
| decode-1MB-Base64UrlNoPad-TextLazy  | 2.012 ms |
| decode-1MB-Base64UrlNoPad-TextShort | 1.976 ms |
| decode-1MB-Base64UrlNoPad-Byte      | 1.895 ms |
| decode-1MB-Base64UrlNoPad-ByteLazy  | 1.932 ms |
| decode-1MB-Base64UrlNoPad-ByteShort | 1.978 ms |
| decode-1MB-N#Base64UrlNoPad-Byte    | 1.969 ms |
| decode-1MB-X#Base64UrlNoPad-Byte    | 1.937 ms |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

| benchmark                              | nodes      | current  | bound        |
| -------------------------------------- | ---------- | -------- | ------------ |
| **encode-1MB-Base64UrlNoPad-ByteLazy** | **marvin** | 452.0 μs | **485.0 μs** |
| encode-1MB-Base64UrlNoPad-ByteLazy     | zaphod     | 452.0 μs | 352.0 μs     |

## Notes

The following observations concerning these results have been logged:

### [Unreleased]

#### Base64UrlNoPad-decode

* _decode times appear to be somewhat greater than expected_ ([@cdornan], 2023-02-01)

    This needs further investigation.

### [0.0.0.1]

#### Base64UrlNoPad-encode

* _lazy encode pipelines slightly better -- for now_ ([@cdornan], 2023-02-01)

    We hope to fix this soon in a coming release.

[Unreleased]: <https://github.com/cdornan/polymede-benchmarks>
[0.0.0.1]: <https://github.com/cdornan/polymede-benchmarks>
[@cdornan]: <https://github.com/cdornan>

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base64UrlNoPad-decode]
* [Base64UrlNoPad-encode]
* [Base64UrlNoPad-hack]
* [Base64UrlNoPad-misc]

[Base64UrlNoPad-hack]: <./Base64UrlNoPad-hack/index.html>
[Base64UrlNoPad-encode]: <./Base64UrlNoPad-encode/index.html>
[Base64UrlNoPad-misc]: <./Base64UrlNoPad-misc/index.html>
[Base64UrlNoPad-decode]: <./Base64UrlNoPad-decode/index.html>

