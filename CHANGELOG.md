# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.2] - 2022-05-27
### Added
- Add an error log to handle a case where EAN number cannot be updated to Monitor when client registers an order with a new variant code and manually changes status of order historically.

## [1.0.1] - 2022-05-10
### Added
- Delete .exe temporary files
### Fixed
- Deleted CustomerOrderRows are filtered out and skipped
### Changed 
- Log rotation is changed from 1 day to every day at 00:00

## [1.0.0] - 2022-05-04
### Added
- Ready