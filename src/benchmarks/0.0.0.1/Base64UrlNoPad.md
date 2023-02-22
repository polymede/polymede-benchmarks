# Base64UrlNoPad

This folder contains the benchmark results for the Base64UrlNoPad compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* encodes 25 bytes in **114.6 ns** using the **Byte** pipeline
* decodes to 25 bytes in **162.7 ns** using the **Byte** pipeline

## Results Summary

| benchmark                      | duration |
| ------------------------------ | -------- |
| encode-25B-Base64UrlNoPad-Byte | 114.6 ns |
| decode-25B-Base64UrlNoPad-Byte | 162.7 ns |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base64UrlNoPad-decode]
* [Base64UrlNoPad-encode]
* [Base64UrlNoPad-misc]

[Base64UrlNoPad-encode]: <./Base64UrlNoPad-encode/index.html>
[Base64UrlNoPad-misc]: <./Base64UrlNoPad-misc/index.html>
[Base64UrlNoPad-decode]: <./Base64UrlNoPad-decode/index.html>

