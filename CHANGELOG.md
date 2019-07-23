# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
- `free_from_str` and `free_from_fn`.

### Changed
- `value_from_fn` allows any error type that implements `Display` now
  and not only `String`.
- `from_args` -> `from_vec`.
- `from_env` returns a `Result` now.
- The `Error` enum.

### Fixed
- Do not panic while parsing non UTF-8 arguments.

[Unreleased]: https://github.com/RazrFalcon/ttf-parser/compare/v0.1.0...HEAD