# Base32NoPadLower

This folder contains the benchmark results for the Base32NoPadLower compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* decodes to 25 bytes in **118.2 ns** using the **Byte** pipeline
* encodes 25 bytes in **176.6 ns** using the **Byte** pipeline

## Results Summary

| benchmark                        | duration |
| -------------------------------- | -------- |
| encode-25B-Base32NoPadLower-Byte | 176.6 ns |
| decode-25B-Base32NoPadLower-Byte | 118.2 ns |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base32NoPadLower-decode]
* [Base32NoPadLower-encode]
* [Base32NoPadLower-misc]

[Base32NoPadLower-decode]: <./Base32NoPadLower-decode/index.html>
[Base32NoPadLower-misc]: <./Base32NoPadLower-misc/index.html>
[Base32NoPadLower-encode]: <./Base32NoPadLower-encode/index.html>

