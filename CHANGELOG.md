# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

*Nothing here yet*

## [v0.4.0]
### Added
- Support for Background. Refs #57
- **API break**, Merged `--feature-tags` and `--scenario-tags` to `--tags` command line option. Refs #72
- Pinned colorful version to 0.1.3 until new colorful version is out.

## [v0.3.2]

### Changed
- Disabled the *syslog extension* by default. It can be enabled via the `--syslog` command line option. Refs #49

## [v0.3.1]

### Fixed
- Remove vendored `parse` package because [parse (#38)](https://github.com/r1chardj0n3s/parse/pull/38) is merged

## [v0.3.0]

### Added
- Vendor `parse` package until [parse (#38)](https://github.com/r1chardj0n3s/parse/pull/38) is merged
- Implement `radish-test` to test step patterns
- Improved coverage extensions with useful CLI options. Refs #15 and #41
- Support for [tag-expressions](https://github.com/timofurrer/tag-expressions) for `--feature-tags` and `--scenario-tags`. Refs #16

### Fixed
- Lazy evaluate matched step arguments. Refs #31
- Support running features containing steps with missing step definitions if they are ignored by tags. Refs #17

## [v0.2.12]
### Added
- Python 3.6 support
- Python 3.7-dev support (allowed to fail)


## No previous changelog history.

Please see `git log`

[Unreleased]: https://github.com/radish-bdd/radish/compare/v0.4.0...HEAD
[v0.4.0]: https://github.com/radish-bdd/radish/compare/v0.3.2...v0.4.0
[v0.3.2]: https://github.com/radish-bdd/radish/compare/v0.3.1...v0.3.2
[v0.3.1]: https://github.com/radish-bdd/radish/compare/v0.3.0...v0.3.1
[v0.3.0]: https://github.com/radish-bdd/radish/compare/v0.2.12...v0.3.0
[v0.2.12]: https://github.com/radish-bdd/radish/compare/v0.2.11...v0.2.12
