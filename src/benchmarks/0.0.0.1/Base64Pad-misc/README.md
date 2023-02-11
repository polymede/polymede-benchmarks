# Base64Pad-misc

This folder contains the Base64Pad misc benchmarks compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2 (22D49).

## Key Results

* There are no highlighted benchmarks.

## Results Summary

| benchmark                       | duration |
| ------------------------------- | -------- |
| encode-1MB-N#Base64Pad-Byte     | 451.6 μs |
| encode-1MB-N#Base64Pad-ByteLazy | 451.4 μs |
| encode-1MB-X#Base64Pad-Byte     | 479.4 μs |
| encode-1MB-X#Base64Pad-ByteLazy | 451.7 μs |
| decode-1MB-N#Base64Pad-Byte     | 1.893 ms |
| decode-1MB-N#Base64Pad-ByteLazy | 1.892 ms |

See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

[criterion.html](criterion.html)

