# Base64UrlNoPad-misc

This folder contains the Base64UrlNoPad misc benchmarks compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2 (22D49).

## Key Results

* There are no highlighted benchmarks.

## Results Summary

| benchmark                            | duration |
| ------------------------------------ | -------- |
| encode-1MB-N#Base64UrlNoPad-Byte     | 451.6 μs |
| encode-1MB-N#Base64UrlNoPad-ByteLazy | 451.6 μs |
| encode-1MB-X#Base64UrlNoPad-Byte     | 479.5 μs |
| encode-1MB-X#Base64UrlNoPad-ByteLazy | 452.0 μs |
| decode-1MB-N#Base64UrlNoPad-Byte     | 1.939 ms |
| decode-1MB-N#Base64UrlNoPad-ByteLazy | 1.936 ms |

See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

[criterion.html](criterion.html)

