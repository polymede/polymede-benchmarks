# Base32HexNoPadUpper

This folder contains the benchmark results for the Base32HexNoPadUpper compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* decodes to 25 bytes in **118.1 ns** using the **Byte** pipeline
* encodes 25 bytes in **110.1 ns** using the **Byte** pipeline

## Results Summary

| benchmark                           | duration |
| ----------------------------------- | -------- |
| encode-25B-Base32HexNoPadUpper-Byte | 110.1 ns |
| decode-25B-Base32HexNoPadUpper-Byte | 118.1 ns |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base32HexNoPadUpper-decode]
* [Base32HexNoPadUpper-encode]
* [Base32HexNoPadUpper-misc]

[Base32HexNoPadUpper-decode]: <./Base32HexNoPadUpper-decode/index.html>
[Base32HexNoPadUpper-misc]: <./Base32HexNoPadUpper-misc/index.html>
[Base32HexNoPadUpper-encode]: <./Base32HexNoPadUpper-encode/index.html>

