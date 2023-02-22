# Base32NoPadUpper

This folder contains the benchmark results for the Base32NoPadUpper compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* decodes to 25 bytes in **118.4 ns** using the **Byte** pipeline
* encodes 25 bytes in **110.2 ns** using the **Byte** pipeline

## Results Summary

| benchmark                        | duration |
| -------------------------------- | -------- |
| encode-25B-Base32NoPadUpper-Byte | 110.2 ns |
| decode-25B-Base32NoPadUpper-Byte | 118.4 ns |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base32NoPadUpper-decode]
* [Base32NoPadUpper-encode]
* [Base32NoPadUpper-misc]

[Base32NoPadUpper-decode]: <./Base32NoPadUpper-decode/index.html>
[Base32NoPadUpper-encode]: <./Base32NoPadUpper-encode/index.html>
[Base32NoPadUpper-misc]: <./Base32NoPadUpper-misc/index.html>

