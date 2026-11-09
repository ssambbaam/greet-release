# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- `greet()` takes a `punctuation` argument: the ending was always `!` → `greet("Hee", ".")` returns `Hello, Hee.`.

### Fixed

- `greet()` with an empty or blank name: returned `Hello, !` → returns `Hello, world!`.

## [0.1.0] - 2026-11-09

### Added

- `greet()` and a command-line greeting: `python greet.py Hee` prints `Hello, Hee!`.

[unreleased]: https://github.com/ssambbaam/greet-release/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/ssambbaam/greet-release/releases/tag/v0.1.0
