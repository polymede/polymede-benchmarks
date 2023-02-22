# Base32HexPadUpper-decode

This folder contains the decode benchmarks for the **Base32HexPadUpper** codec compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* decodes to 25 bytes in **118.2 ns** using the **Byte** pipeline

## Results Summary

| benchmark                         | duration |
| --------------------------------- | -------- |
| decode-25B-Base32HexPadUpper-Byte | 118.2 ns |

See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

[criterion.html](criterion.html)
