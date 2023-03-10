# Base64UrlNoPad-encode

This folder contains the encode benchmarks for the **Base64UrlNoPad** codec compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* There are no highlighted benchmarks.

## Results Summary

| benchmark                            | duration |
| ------------------------------------ | -------- |
| encode-0025B-Base64UrlNoPad-ByteLazy | 259.1 ns |
| encode-010KB-Base64UrlNoPad-ByteLazy | 4.767 μs |
| encode-001MB-Base64UrlNoPad-ByteLazy | 455.3 μs |

See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

| benchmark                                | nodes      | current  | bound        |
| ---------------------------------------- | ---------- | -------- | ------------ |
| **encode-001MB-Base64UrlNoPad-ByteLazy** | **marvin** | 455.3 μs | **485.0 μs** |
| encode-001MB-Base64UrlNoPad-ByteLazy     | zaphod     | 455.3 μs | 352.0 μs     |

## Notes

The following observations concerning these results have been logged:

### [0.0.0.1]

#### Base64UrlNoPad-encode

* _lazy encode pipelines slightly better -- for now_ ([@cdornan], 2023-02-01)

    We hope to fix this soon in a coming release.

[Unreleased]: <https://github.com/cdornan/polymede-benchmarks>
[0.0.0.1]: <https://github.com/cdornan/polymede-benchmarks>
[@cdornan]: <https://github.com/cdornan>

[criterion.html](criterion.html)

