# Base64Pad-misc

This folder contains the Base64Pad misc benchmarks compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* There are no highlighted benchmarks.

## Results Summary

| benchmark                         | duration |
| --------------------------------- | -------- |
| encode-0025B-N#Base64Pad-ByteLazy | 189.2 ns |
| encode-0025B-X#Base64Pad-ByteLazy | 211.1 ns |
| encode-010KB-N#Base64Pad-ByteLazy | 4.640 μs |
| encode-010KB-X#Base64Pad-ByteLazy | 4.660 μs |
| encode-001MB-N#Base64Pad-ByteLazy | 452.2 μs |
| encode-001MB-X#Base64Pad-ByteLazy | 452.4 μs |
| decode-0025B-N#Base64Pad-ByteLazy | 123.5 ns |
| decode-010KB-N#Base64Pad-ByteLazy | 19.03 μs |
| decode-001MB-N#Base64Pad-ByteLazy | 1.899 ms |

See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

[criterion.html](criterion.html)

