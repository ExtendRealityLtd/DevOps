# Changelog

## [3.5.4](https://github.com/ExtendRealityLtd/DevOps/compare/v3.5.3...v3.5.4) (2019-01-02)


### Bug Fixes

* **templates:** tarball to zip commands ([54c940c](https://github.com/ExtendRealityLtd/DevOps/commit/54c940c))

## [3.5.3](https://github.com/ExtendRealityLtd/DevOps/compare/v3.5.2...v3.5.3) (2019-01-02)


### Bug Fixes

* **templates:** tarball to zip commands by moving into .sh file ([baec719](https://github.com/ExtendRealityLtd/DevOps/commit/baec719))

## [3.5.2](https://github.com/ExtendRealityLtd/DevOps/compare/v3.5.1...v3.5.2) (2019-01-02)


### Bug Fixes

* **templates:** escape tarball to zip commands ([e39d9d2](https://github.com/ExtendRealityLtd/DevOps/commit/e39d9d2))

## [3.5.1](https://github.com/ExtendRealityLtd/DevOps/compare/v3.5.0...v3.5.1) (2019-01-02)


### Bug Fixes

* **templates:** tarball to zip ([b6f127b](https://github.com/ExtendRealityLtd/DevOps/commit/b6f127b))

# [3.5.0](https://github.com/ExtendRealityLtd/DevOps/compare/v3.4.0...v3.5.0) (2019-01-01)


### Features

* **templates:** publish .zip package to GitHub via CD steps ([240b66a](https://github.com/ExtendRealityLtd/DevOps/commit/240b66a))

# [3.4.0](https://github.com/ExtendRealityLtd/DevOps/compare/v3.3.6...v3.4.0) (2018-12-23)


### Features

* **templates:** ignore npm notice "errors" in CD steps ([a1c30ee](https://github.com/ExtendRealityLtd/DevOps/commit/a1c30ee))

## [3.3.6](https://github.com/ExtendRealityLtd/DevOps/compare/v3.3.5...v3.3.6) (2018-12-23)


### Bug Fixes

* **templates:** encoding issue in CD steps ([23dcc94](https://github.com/ExtendRealityLtd/DevOps/commit/23dcc94))

## [3.3.5](https://github.com/ExtendRealityLtd/DevOps/compare/v3.3.4...v3.3.5) (2018-12-23)


### Bug Fixes

* **templates:** double if in conditional expressions in CI steps ([d8314c2](https://github.com/ExtendRealityLtd/DevOps/commit/d8314c2))

## [3.3.4](https://github.com/ExtendRealityLtd/DevOps/compare/v3.3.3...v3.3.4) (2018-12-23)


### Bug Fixes

* **templates:** move Unity .meta files check to CD steps ([d53d41c](https://github.com/ExtendRealityLtd/DevOps/commit/d53d41c))
* **templates:** unityProject parameter check ([1da33c8](https://github.com/ExtendRealityLtd/DevOps/commit/1da33c8))

## [3.3.3](https://github.com/ExtendRealityLtd/DevOps/compare/v3.3.2...v3.3.3) (2018-12-22)


### Bug Fixes

* **templates:** check Unity .meta files after building, not before ([cb387f1](https://github.com/ExtendRealityLtd/DevOps/commit/cb387f1))

## [3.3.2](https://github.com/ExtendRealityLtd/DevOps/compare/v3.3.1...v3.3.2) (2018-12-22)


### Bug Fixes

* **templates:** syntax of conditional insertion for task arguments ([83703af](https://github.com/ExtendRealityLtd/DevOps/commit/83703af))

## [3.3.1](https://github.com/ExtendRealityLtd/DevOps/compare/v3.3.0...v3.3.1) (2018-12-22)


### Bug Fixes

* **templates:** fail on Unity .meta files for no matching file ([e13d988](https://github.com/ExtendRealityLtd/DevOps/commit/e13d988))

# [3.3.0](https://github.com/ExtendRealityLtd/DevOps/compare/v3.2.0...v3.3.0) (2018-12-22)


### Features

* **templates:** ensure Unity projects have the needed .meta files ([260603d](https://github.com/ExtendRealityLtd/DevOps/commit/260603d))

# [3.2.0](https://github.com/ExtendRealityLtd/DevOps/compare/v3.1.0...v3.2.0) (2018-12-20)


### Features

* **templates:** use latest semantic-release versions ([005ecef](https://github.com/ExtendRealityLtd/DevOps/commit/005ecef))

# [3.1.0](https://github.com/ExtendRealityLtd/DevOps/compare/v3.0.0...v3.1.0) (2018-12-17)


### Bug Fixes

* **templates:** apply environment variables to semantic-release task ([f481237](https://github.com/ExtendRealityLtd/DevOps/commit/f481237))
* **templates:** token variable name for GitHub ([72f4f7a](https://github.com/ExtendRealityLtd/DevOps/commit/72f4f7a))


### Features

* **templates:** publish to npmjs.org ([87fae9f](https://github.com/ExtendRealityLtd/DevOps/commit/87fae9f))

# [3.0.0](https://github.com/ExtendRealityLtd/DevOps/compare/v2.0.1...v3.0.0) (2018-12-17)


### Bug Fixes

* **templates:** use NuGet 4.x but no later version ([987bfb9](https://github.com/ExtendRealityLtd/DevOps/commit/987bfb9))


### BREAKING CHANGES

* **templates:** only NuGet 4.x will be used until all projects are
confirmed to work with a later major release of NuGet.

## [2.0.1](https://github.com/ExtendRealityLtd/DevOps/compare/v2.0.0...v2.0.1) (2018-12-17)


### Bug Fixes

* **templates:** semantic-release success comment ([7514371](https://github.com/ExtendRealityLtd/DevOps/commit/7514371)), closes [#4](https://github.com/ExtendRealityLtd/DevOps/issues/4)

# [2.0.0](https://github.com/ExtendRealityLtd/DevOps/compare/v1.0.1...v2.0.0) (2018-12-16)


### Bug Fixes

* **templates:** allow using semantic-release template in other repos ([6937366](https://github.com/ExtendRealityLtd/DevOps/commit/6937366))


### chore

* **templates:** don't log debug information from semantic-release ([1607967](https://github.com/ExtendRealityLtd/DevOps/commit/1607967))


### BREAKING CHANGES

* **templates:** The CD template no longer includes debug
information of semantic-release.

## [1.0.1](https://github.com/ExtendRealityLtd/DevOps/compare/v1.0.0...v1.0.1) (2018-12-16)


### Bug Fixes

* **package:** change description from Malimbe repository ([3ed0ce9](https://github.com/ExtendRealityLtd/DevOps/commit/3ed0ce9))

## [1.0.1-prerelease.1](https://github.com/ExtendRealityLtd/DevOps/compare/v1.0.0...v1.0.1-prerelease.1@prerelease) (2018-12-16)


### Bug Fixes

* **package:** change description from Malimbe repository ([3ed0ce9](https://github.com/ExtendRealityLtd/DevOps/commit/3ed0ce9))

# 1.0.0 (2018-12-16)


### Features

* **templates:** add CI and CD templates for Azure Pipelines ([ebdc9b5](https://github.com/ExtendRealityLtd/DevOps/commit/ebdc9b5))
