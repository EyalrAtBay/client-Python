# Changelog

## [Unreleased]

## [5.2.5]
### Fixed
- Issue [#194](https://github.com/reportportal/client-Python/issues/194): logging URL generation, by @HardNorth
- Issue [#195](https://github.com/reportportal/client-Python/issues/195): `None` mode exception, by @HardNorth

## [5.2.4]
### Changed
- `LogManager` class moved from `core` package to `logs` package, by @HardNorth
### Fixed
- Issue [#192](https://github.com/reportportal/client-Python/issues/192): launch URL generation, by @HardNorth

## [5.2.3]
### Added
- Ability to pass client instance in `RPLogHandler` constructor, by @HardNorth
- Issue [#179](https://github.com/reportportal/client-Python/issues/179): batch logging request payload size tracking, by @HardNorth
### Fixed
- Issue [#184](https://github.com/reportportal/client-Python/issues/184): early logger initialization exception, by @dagansandler

## [5.2.2]
### Fixed
- Issue [#182](https://github.com/reportportal/client-Python/issues/182): logger crash on empty client, by @HardNorth

## [5.2.1]
### Fixed
- Issue [#180](https://github.com/reportportal/client-Python/issues/180): logger crash on attachments, by @HardNorth
### Changed
- Log processing does not stop on the first error now, by @HardNorth

## [5.2.0]
### Changed
- Client fixes, by @HardNorth
