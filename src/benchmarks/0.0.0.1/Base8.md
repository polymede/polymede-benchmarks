# Base8

This folder contains the benchmark results for the Base8 compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* decodes to 25 bytes in **10.70 μs** using the **Byte** pipeline
* encodes 25 bytes in **1.355 μs** using the **Byte** pipeline

## Results Summary

| benchmark             | duration |
| --------------------- | -------- |
| encode-25B-Base8-Byte | 1.355 μs |
| decode-25B-Base8-Byte | 10.70 μs |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base8-decode]
* [Base8-encode]
* [Base8-misc]

[Base8-decode]: <./Base8-decode/index.html>
[Base8-misc]: <./Base8-misc/index.html>
[Base8-encode]: <./Base8-encode/index.html>

