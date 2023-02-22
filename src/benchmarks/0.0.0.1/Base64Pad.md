# Base64Pad

This folder contains the benchmark results for the Base64Pad compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* encodes 25 bytes in **116.1 ns** using the **Byte** pipeline
* decodes to 25 bytes in **136.1 ns** using the **Byte** pipeline

## Results Summary

| benchmark                 | duration |
| ------------------------- | -------- |
| encode-25B-Base64Pad-Byte | 116.1 ns |
| decode-25B-Base64Pad-Byte | 136.1 ns |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base64Pad-decode]
* [Base64Pad-encode]
* [Base64Pad-misc]

[Base64Pad-encode]: <./Base64Pad-encode/index.html>
[Base64Pad-misc]: <./Base64Pad-misc/index.html>
[Base64Pad-decode]: <./Base64Pad-decode/index.html>

