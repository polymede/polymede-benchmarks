# Base32HexPadLower

This folder contains the benchmark results for the Base32HexPadLower compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* decodes to 25 bytes in **118.2 ns** using the **Byte** pipeline
* encodes 25 bytes in **174.0 ns** using the **Byte** pipeline

## Results Summary

| benchmark                         | duration |
| --------------------------------- | -------- |
| encode-25B-Base32HexPadLower-Byte | 174.0 ns |
| decode-25B-Base32HexPadLower-Byte | 118.2 ns |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base32HexPadLower-decode]
* [Base32HexPadLower-encode]
* [Base32HexPadLower-misc]

[Base32HexPadLower-decode]: <./Base32HexPadLower-decode/index.html>
[Base32HexPadLower-misc]: <./Base32HexPadLower-misc/index.html>
[Base32HexPadLower-encode]: <./Base32HexPadLower-encode/index.html>

