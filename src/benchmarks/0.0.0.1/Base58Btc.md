# Base58Btc

This folder contains the benchmark results for the Base58Btc compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* encodes 25 bytes in **3.050 μs** using the **Byte** pipeline
* decodes to 25 bytes in **3.910 μs** using the **Byte** pipeline

## Results Summary

| benchmark                 | duration |
| ------------------------- | -------- |
| encode-25B-Base58Btc-Byte | 3.050 μs |
| decode-25B-Base58Btc-Byte | 3.910 μs |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base58Btc-decode]
* [Base58Btc-encode]
* [Base58Btc-misc]

[Base58Btc-encode]: <./Base58Btc-encode/index.html>
[Base58Btc-misc]: <./Base58Btc-misc/index.html>
[Base58Btc-decode]: <./Base58Btc-decode/index.html>

