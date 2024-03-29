# Change Log

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## 0.0.29 - 2023-11-22
### Fixed
- Fix font integration
### Changed
- Reduce app size by removing unused code
- Modernize the toolchain (Rollup instead of Browserify with Babel)

## 0.0.25 - 2023-04-11
### Fixed
- Fix incorrect calculation for playback devices with a sample rate differing from 48 kHz

## 0.0.24 - 2023-04-08
### Changed
- Reduce startup time by using already normalized audio samples
- Reduce range of dynamic for electric guitar and nylon guitar
- Optimize the aduio signal for children's xylophone

## 0.0.22 - 2023-02-18
### Changed
- Use a single file for all audio samples
### Added
- Show the currently played notes
