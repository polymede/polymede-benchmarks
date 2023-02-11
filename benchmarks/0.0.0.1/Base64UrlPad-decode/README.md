# Base64UrlPad-decode

This folder contains the decode benchmarks for the **Base64UrlPad** codec compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2 (22D49).

## Key Results

* decodes to 1,000,000 bytes in **1.901 ms** using the **ByteLazy** pipeline

## Results Summary

| benchmark                         | duration |
| --------------------------------- | -------- |
| decode-1MB-Base64UrlPad-Text      | 1.929 ms |
| decode-1MB-Base64UrlPad-TextLazy  | 1.930 ms |
| decode-1MB-Base64UrlPad-TextShort | 1.954 ms |
| decode-1MB-Base64UrlPad-Byte      | 1.911 ms |
| decode-1MB-Base64UrlPad-ByteLazy  | 1.901 ms |
| decode-1MB-Base64UrlPad-ByteShort | 1.961 ms |

See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:

### [Unreleased]

#### Base64UrlPad-decode

* _decode times appear to be somewhat greater than expected_ ([@cdornan], 2023-02-01)

    This needs further investigation.

[Unreleased]: <https://github.com/cdornan/polymede-benchmarks>
[@cdornan]: <https://github.com/cdornan>

[criterion.html](criterion.html)

