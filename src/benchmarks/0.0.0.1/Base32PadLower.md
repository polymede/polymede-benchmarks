# Base32PadLower

This folder contains the benchmark results for the Base32PadLower compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* encodes 25 bytes in **169.4 ns** using the **Byte** pipeline
* decodes to 25 bytes in **117.7 ns** using the **Byte** pipeline

## Results Summary

| benchmark                      | duration |
| ------------------------------ | -------- |
| encode-25B-Base32PadLower-Byte | 169.4 ns |
| decode-25B-Base32PadLower-Byte | 117.7 ns |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base32PadLower-decode]
* [Base32PadLower-encode]
* [Base32PadLower-misc]

[Base32PadLower-encode]: <./Base32PadLower-encode/index.html>
[Base32PadLower-misc]: <./Base32PadLower-misc/index.html>
[Base32PadLower-decode]: <./Base32PadLower-decode/index.html>

