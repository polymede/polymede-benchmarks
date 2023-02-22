# Proquint

This folder contains the benchmark results for the Proquint compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* decodes to 25 bytes in **1.741 μs** using the **Byte** pipeline
* encodes 25 bytes in **1.486 μs** using the **Byte** pipeline

## Results Summary

| benchmark                | duration |
| ------------------------ | -------- |
| encode-25B-Proquint-Byte | 1.486 μs |
| decode-25B-Proquint-Byte | 1.741 μs |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Proquint-decode]
* [Proquint-encode]
* [Proquint-misc]

[Proquint-decode]: <./Proquint-decode/index.html>
[Proquint-encode]: <./Proquint-encode/index.html>
[Proquint-misc]: <./Proquint-misc/index.html>

