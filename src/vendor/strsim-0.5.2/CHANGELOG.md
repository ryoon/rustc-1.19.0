# Change Log
This project attempts to adhere to [Semantic Versioning](http://semver.org).

## [0.5.2] - (2016-11-21)
### Changed
- Remove Cargo generated documentation in favor of a [docs.rs] link

## [0.5.1] - (2016-08-23)
### Added
- Add Cargo generated documentation

### Fixed
- Fix panic when Jaro or Jaro-Winkler are given strings both with a length of
one

## [0.5.0] - (2016-08-11)
### Changed
- Make Hamming faster (thanks @IBUzPE9) when the two strings have the same
length but slower when they have different lengths

## [0.4.1] - (2016-04-18)
### Added
- Add Vagrant setup for development
- Add AppVeyor configuration for Windows CI

### Fixed
- Fix metrics when given strings with multibyte characters (thanks @WanzenBug)

## [0.4.0] - (2015-06-10)
### Added
- For each metric, add a function that takes a vector of strings and returns a
vector of results (thanks @ovarene)

## [0.3.0] - (2015-04-30)
### Changed
- Remove usage of unstable Rust features

## [0.2.5] - (2015-04-24)
### Fixed
- Remove unnecessary `Float` import from doc tests

## [0.2.4] - (2015-04-15)
### Fixed
- Remove unused `core` feature flag

## [0.2.3] - (2015-04-01)
### Fixed
- Remove now unnecessary `Float` import

## [0.2.2] - (2015-03-29)
### Fixed
- Remove usage of `char_at` (marked as unstable)

## [0.2.1] - (2015-02-20)
### Fixed
- Update bit vector import to match Rust update

## [0.2.0] - (2015-02-19)
### Added
- Implement Damerau-Levenshtein
- Add tests in docs

## [0.1.1] - (2015-02-10)
### Added
- Configure Travis for CI
- Add rustdoc comments

### Fixed
- Limit Jaro-Winkler return value to a maximum of 1.0
- Fix float comparsions in tests

## [0.1.0] - (2015-02-09)
### Added
- Implement Hamming, Jaro, Jaro-Winkler, and Levenshtein

[Unreleased]: https://github.com/dguo/strsim-rs/compare/0.5.2...HEAD
[0.5.2]: https://github.com/dguo/strsim-rs/compare/0.5.1...0.5.2
[0.5.1]: https://github.com/dguo/strsim-rs/compare/0.5.0...0.5.1
[0.5.0]: https://github.com/dguo/strsim-rs/compare/0.4.1...0.5.0
[0.4.1]: https://github.com/dguo/strsim-rs/compare/0.4.0...0.4.1
[0.4.0]: https://github.com/dguo/strsim-rs/compare/0.3.0...0.4.0
[0.3.0]: https://github.com/dguo/strsim-rs/compare/0.2.5...0.3.0
[0.2.5]: https://github.com/dguo/strsim-rs/compare/0.2.4...0.2.5
[0.2.4]: https://github.com/dguo/strsim-rs/compare/0.2.3...0.2.4
[0.2.3]: https://github.com/dguo/strsim-rs/compare/0.2.2...0.2.3
[0.2.2]: https://github.com/dguo/strsim-rs/compare/0.2.1...0.2.2
[0.2.1]: https://github.com/dguo/strsim-rs/compare/0.2.0...0.2.1
[0.2.0]: https://github.com/dguo/strsim-rs/compare/0.1.1...0.2.0
[0.1.1]: https://github.com/dguo/strsim-rs/compare/0.1.0...0.1.1
[0.1.0]: https://github.com/dguo/strsim-rs/compare/fabad4...0.1.0
[docs.rs]: https://docs.rs/strsim/

