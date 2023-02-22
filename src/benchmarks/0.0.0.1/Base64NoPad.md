# Base64NoPad

This folder contains the benchmark results for the Base64NoPad compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* decodes to 25 bytes in **184.3 ns** using the **Byte** pipeline
* encodes 25 bytes in **143.7 ns** using the **Byte** pipeline

## Results Summary

| benchmark                   | duration |
| --------------------------- | -------- |
| encode-25B-Base64NoPad-Byte | 143.7 ns |
| decode-25B-Base64NoPad-Byte | 184.3 ns |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base64NoPad-decode]
* [Base64NoPad-encode]
* [Base64NoPad-misc]

[Base64NoPad-misc]: <./Base64NoPad-misc/index.html>
[Base64NoPad-decode]: <./Base64NoPad-decode/index.html>
[Base64NoPad-encode]: <./Base64NoPad-encode/index.html>

