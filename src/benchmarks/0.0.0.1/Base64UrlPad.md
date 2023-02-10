# Base64UrlPad

This folder contains the benchmark results for the Base64UrlPad compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2 (22D49).

## Key Results

* encodes 1,000,000 bytes in **453.2 μs** using the **ByteLazy** pipeline
* decodes to 1,000,000 bytes in **1.888 ms** using the **ByteLazy** pipeline

## Results Summary

| benchmark                         | duration |
| --------------------------------- | -------- |
| encode-1MB-Base64UrlPad-Text      | 526.9 μs |
| encode-1MB-Base64UrlPad-TextLazy  | 500.1 μs |
| encode-1MB-Base64UrlPad-TextShort | 514.4 μs |
| encode-1MB-Base64UrlPad-Byte      | 483.9 μs |
| encode-1MB-Base64UrlPad-ByteLazy  | 453.2 μs |
| encode-1MB-Base64UrlPad-ByteShort | 509.8 μs |
| decode-1MB-Base64UrlPad-Text      | 1.935 ms |
| decode-1MB-Base64UrlPad-TextLazy  | 1.942 ms |
| decode-1MB-Base64UrlPad-TextShort | 1.957 ms |
| decode-1MB-Base64UrlPad-Byte      | 1.896 ms |
| decode-1MB-Base64UrlPad-ByteLazy  | 1.888 ms |
| decode-1MB-Base64UrlPad-ByteShort | 1.950 ms |
| decode-1MB-N#Base64UrlPad-Byte    | 1.887 ms |
| decode-1MB-X#Base64UrlPad-Byte    | 1.890 ms |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

| benchmark                            | nodes      | current  | bound        |
| ------------------------------------ | ---------- | -------- | ------------ |
| **encode-1MB-Base64UrlPad-ByteLazy** | **marvin** | 453.2 μs | **485.0 μs** |
| encode-1MB-Base64UrlPad-ByteLazy     | zaphod     | 453.2 μs | 352.0 μs     |

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
* [Base64UrlPad-hack]
* [Base64UrlPad-misc]

[Base64UrlPad-misc]: <./Base64UrlPad-misc/index.html>
[Base64UrlPad-encode]: <./Base64UrlPad-encode/index.html>
[Base64UrlPad-hack]: <./Base64UrlPad-hack/index.html>
[Base64UrlPad-decode]: <./Base64UrlPad-decode/index.html>

