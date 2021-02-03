# Changelog

### [3.12.4](https://github.com/ExtendRealityLtd/DevOps/compare/v3.12.3...v3.12.4) (2021-02-03)

#### Bug Fixes

* **ci.yml:** wrap version in quotation marks ([1022b9a](https://github.com/ExtendRealityLtd/DevOps/commit/1022b9a667df6e15e31d95d701f8b47e1b85a7a2))
  > The version setter should be wrapped in quotation marks `"` and not apostrophies `'`.

### [3.12.3](https://github.com/ExtendRealityLtd/DevOps/compare/v3.12.2...v3.12.3) (2021-02-03)

#### Bug Fixes

* **ci.yml:** force unity build version if no found ([246a3d7](https://github.com/ExtendRealityLtd/DevOps/commit/246a3d7ad42090129dc30f7c9e404e4e51e49105))
  > If there is no Unity installer present and no Unity version is provided then the process just fails, and for some reason there seems to be no found Unity version so let's force it to be the min supported Unity version.

### [3.12.2](https://github.com/ExtendRealityLtd/DevOps/compare/v3.12.1...v3.12.2) (2020-01-30)

#### Bug Fixes

* **cd.yml:** provide explicit path to find command ([21ca24c](https://github.com/ExtendRealityLtd/DevOps/commit/21ca24c519d732e83fba030c646196d11f2925b4))
  > There is an existing issue with win64 agents trying to run the find command https://github.com/actions/virtual-environments/issues/263
  > 
  > The fix is to provide the explicit path to the find command.

### [3.12.1](https://github.com/ExtendRealityLtd/DevOps/compare/v3.12.0...v3.12.1) (2019-12-21)

#### Bug Fixes

* **templates:** support Unity 2019.2 and later ([6f06dda](https://github.com/ExtendRealityLtd/DevOps/commit/6f06dda51d4d5350a4ae6766b3a4eaf9e5957933))

## [3.12.0](https://github.com/ExtendRealityLtd/DevOps/compare/v3.11.6...v3.12.0) (2019-10-20)

#### Features

* **templates:** bump patch version for dependency updates ([0229eca](https://github.com/ExtendRealityLtd/DevOps/commit/0229eca700018f43dbf3dd6bc346f10e591d55d5))

### [3.11.6](https://github.com/ExtendRealityLtd/DevOps/compare/v3.11.5...v3.11.6) (2019-10-14)

#### Bug Fixes

* **templates:** back to npmjs.com ([f6d295c](https://github.com/ExtendRealityLtd/DevOps/commit/f6d295c83cb21cd261a6efd5d08e24ae7841a801))
  > GitHub's npm feeds only allow publishing scoped packages, but UPM doesn't support those.

### [3.11.5](https://github.com/ExtendRealityLtd/DevOps/compare/v3.11.4...v3.11.5) (2019-10-14)

#### Bug Fixes

* **templates:** use correct NPM registry for package publish ([38f69d7](https://github.com/ExtendRealityLtd/DevOps/commit/38f69d74325cabcd60db2359ab59febb07e881b0))

### [3.11.4](https://github.com/ExtendRealityLtd/DevOps/compare/v3.11.3...v3.11.4) (2019-10-14)

#### Bug Fixes

* **ci:** use package name that is usable by UPM ([c940803](https://github.com/ExtendRealityLtd/DevOps/commit/c940803fb8f88e4b83a8470ce21b17fb1581f8b3))

### [3.11.3](https://github.com/ExtendRealityLtd/DevOps/compare/v3.11.2...v3.11.3) (2019-10-14)

#### Bug Fixes

* **templates:** package release to GitHub ([acb573c](https://github.com/ExtendRealityLtd/DevOps/commit/acb573c8c2143fc09ba92896a835ec6ce857e18d))

### [3.11.2](https://github.com/ExtendRealityLtd/DevOps/compare/v3.11.1...v3.11.2) (2019-10-14)

#### Bug Fixes

* **ci:** empty change to fix package creation ([88cd8c2](https://github.com/ExtendRealityLtd/DevOps/commit/88cd8c2c0e38bc3abb341f2e497b615b99ee6cab))

### [3.11.1](https://github.com/ExtendRealityLtd/DevOps/compare/v3.11.0...v3.11.1) (2019-10-14)

#### Bug Fixes

* **packaging:** use GitHub feed compliant package name ([58939ef](https://github.com/ExtendRealityLtd/DevOps/commit/58939efb3e24d4c250c1958d71525f0f5a374239))
* **templates:** use correct npm registry ([cf95d79](https://github.com/ExtendRealityLtd/DevOps/commit/cf95d79fb5db3da93b90d659234160fb20642ebc))

#### Miscellaneous Chores

* **templates:** update to latest semantic-release packages ([1547344](https://github.com/ExtendRealityLtd/DevOps/commit/15473444b7bf7e7a47348bb6b5486726bad6811c))

## [3.11.0](https://github.com/ExtendRealityLtd/DevOps/compare/v3.10.1...v3.11.0) (2019-10-14)

#### Features

* **templates:** publish packages to GitHub npm feed ([e8d1ffc](https://github.com/ExtendRealityLtd/DevOps/commit/e8d1ffc5c987b5dbc216926753917b197ecc6949))

### [3.10.1](https://github.com/ExtendRealityLtd/DevOps/compare/v3.10.0...v3.10.1) (2019-10-14)

#### Bug Fixes

* **templates:** support spaces in file path in Unity .meta checks ([d96d688](https://github.com/ExtendRealityLtd/DevOps/commit/d96d688094536b3ec7f44f8c0f48ede2a9b8a6a7))

## [3.10.0](https://github.com/ExtendRealityLtd/DevOps/compare/v3.9.0...v3.10.0) (2019-10-14)

#### Features

* **templates:** merge commit messages in changelog/release note ([53371ac](https://github.com/ExtendRealityLtd/DevOps/commit/53371ace542626dce2f1124b3d468376a7fde5ae))
  > This keeps paragraphs in the messages as is.

#### Bug Fixes

* **templates:** changelog/release note formatting ([c8a7ee9](https://github.com/ExtendRealityLtd/DevOps/commit/c8a7ee9444849950903823b6b8708dcbae43744e))

## [3.10.0-next.1](https://github.com/ExtendRealityLtd/DevOps/compare/v3.9.0...v3.10.0-next.1) (2019-10-14)

#### Features

* **templates:** merge commit messages in changelog/release note ([53371ac](https://github.com/ExtendRealityLtd/DevOps/commit/53371ace542626dce2f1124b3d468376a7fde5ae))
  > This keeps paragraphs in the messages as is.

#### Bug Fixes

* **templates:** changelog/release note formatting ([c8a7ee9](https://github.com/ExtendRealityLtd/DevOps/commit/c8a7ee9444849950903823b6b8708dcbae43744e))
* **templates:** support spaces in file path in Unity .meta checks ([d96d688](https://github.com/ExtendRealityLtd/DevOps/commit/d96d688094536b3ec7f44f8c0f48ede2a9b8a6a7))

## [3.10.0-next.1](https://github.com/ExtendRealityLtd/DevOps/compare/v3.9.0...v3.10.0-next.1) (2019-10-14)

#### Features

* **templates:** merge commit messages in changelog/release note ([53371ac](https://github.com/ExtendRealityLtd/DevOps/commit/53371ace542626dce2f1124b3d468376a7fde5ae))
  > This keeps paragraphs in the messages as is.

#### Bug Fixes

* **templates:** changelog/release note formatting ([c8a7ee9](https://github.com/ExtendRealityLtd/DevOps/commit/c8a7ee9444849950903823b6b8708dcbae43744e))

## [3.9.0](https://github.com/ExtendRealityLtd/DevOps/compare/v3.8.0...v3.9.0) (2019-10-14)


#### Features

* **templates:** pretty, sorted changelog/release notes in CD ([763cf1d](https://github.com/ExtendRealityLtd/DevOps/commit/763cf1dbc04060bf5e289cdad94fb4f4a19936bf))
#### Bug Fixes

* **templates:** CD failure when commit body is empty ([34f4c71](https://github.com/ExtendRealityLtd/DevOps/commit/34f4c71f6282c624868a6d5c5ff38fa2e7c8088d))* **templates:** changelog/release note breaking change formatting ([7efda24](https://github.com/ExtendRealityLtd/DevOps/commit/7efda24500c52da0a262f549ed32a30c9200419a))* **templates:** release pre-release packages on the default channel ([fdc9579](https://github.com/ExtendRealityLtd/DevOps/commit/fdc9579d621250041d02fe13bdc2a9a0ba614ed8))* **templates:** remove release commits from changelog/release note ([cb47e13](https://github.com/ExtendRealityLtd/DevOps/commit/cb47e13133a89ab531866c37fde1b8ec2eb420e7))

## [3.9.0-next.1](https://github.com/ExtendRealityLtd/DevOps/compare/v3.8.0...v3.9.0-next.1) (2019-10-14)


#### Features

* **templates:** pretty, sorted changelog/release notes in CD ([763cf1d](https://github.com/ExtendRealityLtd/DevOps/commit/763cf1dbc04060bf5e289cdad94fb4f4a19936bf))
#### Bug Fixes

* **templates:** CD failure when commit body is empty ([34f4c71](https://github.com/ExtendRealityLtd/DevOps/commit/34f4c71f6282c624868a6d5c5ff38fa2e7c8088d))* **templates:** changelog/release note breaking change formatting ([7efda24](https://github.com/ExtendRealityLtd/DevOps/commit/7efda24500c52da0a262f549ed32a30c9200419a))* **templates:** release pre-release packages on the default channel ([fdc9579](https://github.com/ExtendRealityLtd/DevOps/commit/fdc9579d621250041d02fe13bdc2a9a0ba614ed8))* **templates:** remove release commits from changelog/release note ([cb47e13](https://github.com/ExtendRealityLtd/DevOps/commit/cb47e13133a89ab531866c37fde1b8ec2eb420e7))

## [3.9.0-next.1](https://github.com/ExtendRealityLtd/DevOps/compare/v3.8.0...v3.9.0-next.1) (2019-10-14)


#### Features

* **templates:** pretty, sorted changelog/release notes in CD ([763cf1d](https://github.com/ExtendRealityLtd/DevOps/commit/763cf1dbc04060bf5e289cdad94fb4f4a19936bf))
#### Bug Fixes

* **templates:** CD failure when commit body is empty ([34f4c71](https://github.com/ExtendRealityLtd/DevOps/commit/34f4c71f6282c624868a6d5c5ff38fa2e7c8088d))* **templates:** release pre-release packages on the default channel ([fdc9579](https://github.com/ExtendRealityLtd/DevOps/commit/fdc9579d621250041d02fe13bdc2a9a0ba614ed8))
#### Miscellaneous Chores

* **release:** set version to 3.6.0-next.1 [skip ci] ([f65d680](https://github.com/ExtendRealityLtd/DevOps/commit/f65d680cdf06fba031fc16638e9c0053021d36e8))
  > ## [3.6.0-next.1](https://github.com/ExtendRealityLtd/DevOps/compare/v3.5.6...v3.6.0-next.1@next) (2019-10-13)
  > 
  > ### Features
  > 
  > * **templates:** adhere to latest workflow conventions ([1583546](https://github.com/ExtendRealityLtd/DevOps/commit/15835462980afbef1dfdb8cf89e6f4fdf5ab0283))
  > * **templates:** treat the master branch as a release branch ([d8b9ad4](https://github.com/ExtendRealityLtd/DevOps/commit/d8b9ad4a756068ab89de88a2203f1603b3a7faad))
  > * **templates:** use latest Windows VM image ([f3df0b9](https://github.com/ExtendRealityLtd/DevOps/commit/f3df0b949e361b4f72dea2a71c79a58c0f130f7c))
  > * **templates:** use universal CI skip commit message ([28e2b3e](https://github.com/ExtendRealityLtd/DevOps/commit/28e2b3e1e2fe998d006962ee7a8b5e4352b53944))
  > 
  > ### Bug Fixes
  > 
  > * **templates:** .meta file check when package has dependencies ([7130b5e](https://github.com/ExtendRealityLtd/DevOps/commit/7130b5eef0299d5d424c2b0788dba0c7110f4b4a))
  > * **templates:** correct path for Unity assemblies ([c1b9801](https://github.com/ExtendRealityLtd/DevOps/commit/c1b9801890acc30c3b67b36bc59d6267b53e8098))
  > * **templates:** MSBuild failing due to trailing slash ([25a8435](https://github.com/ExtendRealityLtd/DevOps/commit/25a843506e5157520569f6d2c2ca71c9a5a5e220))
  > * **templates:** semantic-release configuration file name ([bb0b05d](https://github.com/ExtendRealityLtd/DevOps/commit/bb0b05d1df334fd985e64263764f50522666fa5c))

## [3.8.0](https://github.com/ExtendRealityLtd/DevOps/compare/v3.7.2...v3.8.0) (2019-10-13)


### Features

* **templates:** adhere to latest workflow conventions ([1583546](https://github.com/ExtendRealityLtd/DevOps/commit/15835462980afbef1dfdb8cf89e6f4fdf5ab0283))


### Bug Fixes

* **templates:** semantic-release configuration file name ([bb0b05d](https://github.com/ExtendRealityLtd/DevOps/commit/bb0b05d1df334fd985e64263764f50522666fa5c))

## [3.7.2](https://github.com/ExtendRealityLtd/DevOps/compare/v3.7.1...v3.7.2) (2019-10-13)


### Bug Fixes

* **templates:** MSBuild failing due to trailing slash ([25a8435](https://github.com/ExtendRealityLtd/DevOps/commit/25a843506e5157520569f6d2c2ca71c9a5a5e220))

## [3.7.1](https://github.com/ExtendRealityLtd/DevOps/compare/v3.7.0...v3.7.1) (2019-10-13)


### Bug Fixes

* **templates:** correct path for Unity assemblies ([c1b9801](https://github.com/ExtendRealityLtd/DevOps/commit/c1b9801890acc30c3b67b36bc59d6267b53e8098))

# [3.7.0](https://github.com/ExtendRealityLtd/DevOps/compare/v3.6.0...v3.7.0) (2019-10-13)


### Features

* **templates:** treat the master branch as a release branch ([d8b9ad4](https://github.com/ExtendRealityLtd/DevOps/commit/d8b9ad4a756068ab89de88a2203f1603b3a7faad))

# [3.6.0](https://github.com/ExtendRealityLtd/DevOps/compare/v3.5.6...v3.6.0) (2019-10-13)


### Bug Fixes

* **templates:** .meta file check when package has dependencies ([7130b5e](https://github.com/ExtendRealityLtd/DevOps/commit/7130b5eef0299d5d424c2b0788dba0c7110f4b4a))


### Features

* **templates:** use latest Windows VM image ([f3df0b9](https://github.com/ExtendRealityLtd/DevOps/commit/f3df0b949e361b4f72dea2a71c79a58c0f130f7c))
* **templates:** use universal CI skip commit message ([28e2b3e](https://github.com/ExtendRealityLtd/DevOps/commit/28e2b3e1e2fe998d006962ee7a8b5e4352b53944))

## [3.5.6](https://github.com/ExtendRealityLtd/DevOps/compare/v3.5.5...v3.5.6) (2019-01-02)


### Bug Fixes

* **templates:** correct folders for tarball to zip via bestzip ([6850664](https://github.com/ExtendRealityLtd/DevOps/commit/6850664))

## [3.5.5](https://github.com/ExtendRealityLtd/DevOps/compare/v3.5.4...v3.5.5) (2019-01-02)


### Bug Fixes

* **templates:** tarball to zip via bestzip ([6267e71](https://github.com/ExtendRealityLtd/DevOps/commit/6267e71))

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
