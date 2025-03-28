# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.2.0 (UNRELEASED)
### Added
- `rand_core` feature ([#467])
- `arrayvec` support ([#503])

### Changed
- Zeroize is now optional ([#644])
- Bump `aead` from `0.5` to `0.6` ([#583])
- Bump `aes` from `0.8` to `0.9` ([#583])
- Edition changed to 2024 and MSRV bumped to 1.85 ([#662])
- Relax MSRV policy and allow MSRV bumps in patch releases
- `getrandom` feature renamed as `os_rng` ([#662])

## Removed
- `std` and `stream` features ([#662])

[#467]: https://github.com/RustCrypto/AEADs/pull/467
[#503]: https://github.com/RustCrypto/AEADs/pull/503
[#583]: https://github.com/RustCrypto/AEADs/pull/583
[#644]: https://github.com/RustCrypto/AEADs/pull/644
[#662]: https://github.com/RustCrypto/AEADs/pull/662

## 0.1.0 (2022-07-30)
### Added
- `getrandom` feature ([#446])

### Changed
- Relax `subtle` and `zeroize` requirements ([#360])
- Rust 2021 edition upgrade; MSRV 1.56+ ([#435])
- Bump `aead` crate dependency to v0.5 ([#444])
- Bump `aes` dependency to v0.8 ([#450])

[#360]: https://github.com/RustCrypto/AEADs/pull/360
[#435]: https://github.com/RustCrypto/AEADs/pull/435
[#444]: https://github.com/RustCrypto/AEADs/pull/444
[#446]: https://github.com/RustCrypto/AEADs/pull/446
[#450]: https://github.com/RustCrypto/AEADs/pull/450

## 0.0.2 (2021-07-20)
### Changed
- Pin `zeroize` dependency to v1.3 and `subtle` to v2.4 ([#349])

[#349]: https://github.com/RustCrypto/AEADs/pull/349

## 0.0.1 (2021-06-26)
- Initial release
