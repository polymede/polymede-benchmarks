# Base32PadUpper

This folder contains the benchmark results for the Base32PadUpper compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* encodes 25 bytes in **110.0 ns** using the **Byte** pipeline
* decodes to 25 bytes in **117.9 ns** using the **Byte** pipeline

## Results Summary

| benchmark                      | duration |
| ------------------------------ | -------- |
| encode-25B-Base32PadUpper-Byte | 110.0 ns |
| decode-25B-Base32PadUpper-Byte | 117.9 ns |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base32PadUpper-decode]
* [Base32PadUpper-encode]
* [Base32PadUpper-misc]

[Base32PadUpper-misc]: <./Base32PadUpper-misc/index.html>
[Base32PadUpper-encode]: <./Base32PadUpper-encode/index.html>
[Base32PadUpper-decode]: <./Base32PadUpper-decode/index.html>

