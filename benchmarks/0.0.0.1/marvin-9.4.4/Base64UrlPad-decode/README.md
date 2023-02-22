# Base64UrlPad-decode

This folder contains the decode benchmarks for the **Base64UrlPad** codec compiled with GHC 9.4.4 (aarch64), on the 
**marvin** reference node running macOS 13.2.1 (22D68).

## Key Results

* There are no highlighted benchmarks.

## Results Summary

| benchmark                          | duration |
| ---------------------------------- | -------- |
| decode-0025B-Base64UrlPad-ByteLazy | 178.5 ns |
| decode-001MB-Base64UrlPad-ByteLazy | 1.896 ms |

See [criterion.html](criterion.html) for the full breakdown with detailed methodological notes.

## Release Constraints

The following benchmarks are constrained to run inside the following bounds for each release:

* there are no release constraints for this codec/report

## Notes

The following observations concerning these results have been logged:

### [Unreleased]

#### Base64UrlPad-decode

* _decode times appear to be somewhat greater than expected_ ([@cdornan], 2023-02-01)

    This needs further investigation.

[Unreleased]: <https://github.com/cdornan/polymede-benchmarks>
[@cdornan]: <https://github.com/cdornan>

[criterion.html](criterion.html)

