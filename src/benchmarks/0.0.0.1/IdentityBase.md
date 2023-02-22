# IdentityBase

This folder contains the benchmark results for the IdentityBase compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* decodes to 25 bytes in **52.31 ns** using the **Byte** pipeline
* encodes 25 bytes in **61.04 ns** using the **Byte** pipeline

## Results Summary

| benchmark                    | duration |
| ---------------------------- | -------- |
| encode-25B-IdentityBase-Byte | 61.04 ns |
| decode-25B-IdentityBase-Byte | 52.31 ns |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [IdentityBase-decode]
* [IdentityBase-encode]
* [IdentityBase-misc]

[IdentityBase-decode]: <./IdentityBase-decode/index.html>
[IdentityBase-misc]: <./IdentityBase-misc/index.html>
[IdentityBase-encode]: <./IdentityBase-encode/index.html>

