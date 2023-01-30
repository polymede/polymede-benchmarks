# Base64Pad-decode

This folder contains the decode benchmarks for the **Base64Pad** codec compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2 (22D49).

## Key Results

* decodes to 1,000,000 bytes in **1.936 ms** using the **ByteLazy** pipeline


## Results Summary

| benchmark                      | duration |
| ------------------------------ | -------- |
| decode-1MB-Base64Pad-Text      | 1.933 ms |
| decode-1MB-Base64Pad-TextLazy  | 1.925 ms |
| decode-1MB-Base64Pad-TextShort | 1.955 ms |
| decode-1MB-Base64Pad-Byte      | 1.917 ms |
| decode-1MB-Base64Pad-ByteLazy  | 1.936 ms |
| decode-1MB-Base64Pad-ByteShort | 1.950 ms |


See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec
