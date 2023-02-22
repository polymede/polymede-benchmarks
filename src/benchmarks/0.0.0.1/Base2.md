# Base2

This folder contains the benchmark results for the Base2 compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* decodes to 25 bytes in **20.27 μs** using the **Byte** pipeline
* encodes 25 bytes in **1.956 μs** using the **Byte** pipeline

## Results Summary

| benchmark             | duration |
| --------------------- | -------- |
| encode-25B-Base2-Byte | 1.956 μs |
| decode-25B-Base2-Byte | 20.27 μs |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base2-decode]
* [Base2-encode]
* [Base2-misc]

[Base2-decode]: <./Base2-decode/index.html>
[Base2-misc]: <./Base2-misc/index.html>
[Base2-encode]: <./Base2-encode/index.html>

