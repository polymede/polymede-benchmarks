# Base16Upper

This folder contains the benchmark results for the Base16Upper compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* decodes to 25 bytes in **107.3 ns** using the **Byte** pipeline
* encodes 25 bytes in **182.4 ns** using the **Byte** pipeline

## Results Summary

| benchmark                   | duration |
| --------------------------- | -------- |
| encode-25B-Base16Upper-Byte | 182.4 ns |
| decode-25B-Base16Upper-Byte | 107.3 ns |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base16Upper-decode]
* [Base16Upper-encode]
* [Base16Upper-misc]

[Base16Upper-decode]: <./Base16Upper-decode/index.html>
[Base16Upper-encode]: <./Base16Upper-encode/index.html>
[Base16Upper-misc]: <./Base16Upper-misc/index.html>

