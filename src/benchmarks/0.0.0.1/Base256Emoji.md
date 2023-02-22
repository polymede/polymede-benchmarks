# Base256Emoji

This folder contains the benchmark results for the Base256Emoji compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* encodes 25 bytes in **1.495 μs** using the **Byte** pipeline
* decodes to 25 bytes in **20.76 μs** using the **Byte** pipeline

## Results Summary

| benchmark                    | duration |
| ---------------------------- | -------- |
| encode-25B-Base256Emoji-Byte | 1.495 μs |
| decode-25B-Base256Emoji-Byte | 20.76 μs |

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:
* no notes have been attached to this codec/report

## Breakdown

See the following individual reports for a breakdown with methodological notes, etc.

* [Base256Emoji-decode]
* [Base256Emoji-encode]
* [Base256Emoji-misc]

[Base256Emoji-encode]: <./Base256Emoji-encode/index.html>
[Base256Emoji-misc]: <./Base256Emoji-misc/index.html>
[Base256Emoji-decode]: <./Base256Emoji-decode/index.html>

