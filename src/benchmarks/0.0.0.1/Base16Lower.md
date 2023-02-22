# Base16Lower

This folder contains the benchmark results for the Base16Lower compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* decodes to 25 bytes in **107.6 ns** using the **Byte** pipeline
* encodes 25 bytes in **111.8 ns** using the **Byte** pipeline

## Results Summary

| benchmark                   | duration |
| --------------------------- | -------- |
| encode-25B-Base16Lower-Byte | 111.8 ns |
| decode-25B-Base16Lower-Byte | 107.6 ns |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base16Lower-decode]
* [Base16Lower-encode]
* [Base16Lower-misc]

[Base16Lower-decode]: <./Base16Lower-decode/index.html>
[Base16Lower-misc]: <./Base16Lower-misc/index.html>
[Base16Lower-encode]: <./Base16Lower-encode/index.html>

