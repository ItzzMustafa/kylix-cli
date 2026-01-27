# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.5.0] - 2026-01-27

Initial release as a standalone repository. Previously part of [crane-valley/kylix](https://github.com/crane-valley/kylix).

### Added

- **CLI commands**: keygen, encaps, decaps, sign, verify, info, completions
- **Benchmark feature**: Performance benchmarking with `--features bench`
  - Compare with OpenSSL 3.5+ and liboqs
  - Multiple output formats: text, json, markdown
- **Binary distribution**: Pre-built binaries via cargo-dist
  - Linux (x64, ARM64)
  - macOS (x64, ARM64)
  - Windows (x64)
- **Shell completions**: Bash, Zsh, Fish, PowerShell

### Algorithms

All algorithms from kylix-pqc 0.4.x:

- **ML-KEM** (FIPS 203): ML-KEM-512, ML-KEM-768, ML-KEM-1024
- **ML-DSA** (FIPS 204): ML-DSA-44, ML-DSA-65, ML-DSA-87
- **SLH-DSA** (FIPS 205): All SHAKE variants (128s/f, 192s/f, 256s/f)

[Unreleased]: https://github.com/crane-valley/kylix-cli/compare/v0.5.0...HEAD
[0.5.0]: https://github.com/crane-valley/kylix-cli/releases/tag/v0.5.0
