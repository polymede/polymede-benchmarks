# Base64Pad-decode

This folder contains the decode benchmarks for the **Base64Pad** codec compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2 (22D49).

## Key Results

* decodes to 1,000,000 bytes in **1.894 ms** using the **ByteLazy** pipeline

## Results Summary

| benchmark                      | duration |
| ------------------------------ | -------- |
| decode-1MB-Base64Pad-Text      | 1.922 ms |
| decode-1MB-Base64Pad-TextLazy  | 1.922 ms |
| decode-1MB-Base64Pad-TextShort | 1.948 ms |
| decode-1MB-Base64Pad-Byte      | 1.895 ms |
| decode-1MB-Base64Pad-ByteLazy  | 1.894 ms |
| decode-1MB-Base64Pad-ByteShort | 1.950 ms |

See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:

### [Unreleased]

#### Base64Pad-decode

* _decode times appear to be somewhat greater than expected_ ([@cdornan], 2023-02-01)

    This needs further investigation.

[Unreleased]: <https://github.com/cdornan/polymede-benchmarks>
[@cdornan]: <https://github.com/cdornan>

[criterion.html](criterion.html)

