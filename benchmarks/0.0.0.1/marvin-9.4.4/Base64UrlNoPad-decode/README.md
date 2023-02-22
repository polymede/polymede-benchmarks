# Base64UrlNoPad-decode

This folder contains the decode benchmarks for the **Base64UrlNoPad** codec compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* There are no highlighted benchmarks.

## Results Summary

| benchmark                            | duration |
| ------------------------------------ | -------- |
| decode-0025B-Base64UrlNoPad-ByteLazy | 208.1 ns |
| decode-001MB-Base64UrlNoPad-ByteLazy | 1.978 ms |

See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:

### [Unreleased]

#### Base64UrlNoPad-decode

* _decode times appear to be somewhat greater than expected_ ([@cdornan], 2023-02-01)

    This needs further investigation.

[Unreleased]: <https://github.com/cdornan/polymede-benchmarks>
[@cdornan]: <https://github.com/cdornan>

[criterion.html](criterion.html)

