# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1] - 2019-03-30
### Changed
- i3lockr will wait on i3lock if i3lock is called with `--nofork`
- i3lockr will not wait on i3lock if i3lock is not called with `--nofork`
    - this fixes things like `i3lockr && systemctl suspend`

## [0.1.0] - 2019-01-12
### Added
- Initial release
