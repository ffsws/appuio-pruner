# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.0.2] - 2018-11-22
### Fix
- Actually prune images, not deployments in image pruner job

## [2.0.1] - 2018-11-20
### Changed
- Allow pruner to clean up deployment pods
- Allow jobs to re-run on failures

## [2.0.0] - 2018-11-19
### Added
- Reimplementation based around CronJobs

[Unreleased]: https://github.com/appuio/appuio-pruner/compare/v2.0.1...HEAD
[2.0.1]: https://github.com/appuio/appuio-pruner/compare/v2.0.0...v2.0.1
[2.0.0]: https://github.com/appuio/appuio-pruner/compare/v1.0.9...v2.0.0
