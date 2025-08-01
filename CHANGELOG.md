## [1.1.1](https://github.com/omar-dulaimi/prisma-zod-generator/compare/v1.1.0...v1.1.1) (2025-07-30)

### 🐛 Bug Fixes

* improve ESM import handling and type validation ([c07d384](https://github.com/omar-dulaimi/prisma-zod-generator/commit/c07d384d2ec4672271d653446f1c6576f0c2c4d4))
* resolve ESLint errors in ESM configuration tests ([9687c1d](https://github.com/omar-dulaimi/prisma-zod-generator/commit/9687c1d0a2e6d3b6cf703d3bac74bd2c318cd7aa))

### 📚 Documentation

* add preview features support section to README ([a348446](https://github.com/omar-dulaimi/prisma-zod-generator/commit/a348446b379da3ab77c9558eb77a9d27a872c1e9))
* remove beta sections and references from README ([32edf33](https://github.com/omar-dulaimi/prisma-zod-generator/commit/32edf3374c4f96f3e482dc37f79e985ccc1b39f0))

## [1.1.0](https://github.com/omar-dulaimi/prisma-zod-generator/compare/v1.0.7...v1.1.0) (2025-07-25)

### 🚀 Features

* add support for new prisma-client generator ([46cdc02](https://github.com/omar-dulaimi/prisma-zod-generator/commit/46cdc027a0229cc8da648d1daac243b2e62e6748)), closes [#127](https://github.com/omar-dulaimi/prisma-zod-generator/issues/127)

## [1.0.7](https://github.com/omar-dulaimi/prisma-zod-generator/compare/v1.0.6...v1.0.7) (2025-07-25)

### 🐛 Bug Fixes

* add explicit type annotations to prevent TypeScript implicit any errors ([ef50308](https://github.com/omar-dulaimi/prisma-zod-generator/commit/ef503088af6cd0728267a8fb30b9adab782453b8))

## [1.0.6](https://github.com/omar-dulaimi/prisma-zod-generator/compare/v1.0.5...v1.0.6) (2025-07-25)

### 🐛 Bug Fixes

* correct skipDuplicates support for database providers ([0511785](https://github.com/omar-dulaimi/prisma-zod-generator/commit/051178560b0fee4940779c1d941a06f547f16317))

## [1.0.5](https://github.com/omar-dulaimi/prisma-zod-generator/compare/v1.0.4...v1.0.5) (2025-07-25)

### 🐛 Bug Fixes

* remove package/package.json from git add in release workflow ([254ad28](https://github.com/omar-dulaimi/prisma-zod-generator/commit/254ad281cbe1ff5e7b96a85437d72c9917c8a9fc))
* resolve TypeScript compilation errors in generated schemas ([85d10a8](https://github.com/omar-dulaimi/prisma-zod-generator/commit/85d10a8e7f494365d8912120d492e6061d9b52dc))

## [1.0.5](https://github.com/omar-dulaimi/prisma-zod-generator/compare/v1.0.4...v1.0.5) (2025-07-23)

### 🐛 Bug Fixes

* remove package/package.json from git add in release workflow ([254ad28](https://github.com/omar-dulaimi/prisma-zod-generator/commit/254ad281cbe1ff5e7b96a85437d72c9917c8a9fc))

## [1.0.4](https://github.com/omar-dulaimi/prisma-zod-generator/compare/v1.0.3...v1.0.4) (2025-07-23)

### 🐛 Bug Fixes

* remove unused error parameters in test catch blocks ([025b822](https://github.com/omar-dulaimi/prisma-zod-generator/commit/025b82201bb3e615968118c81276f28e3c46874a))
* resolve output directory duplication when path ends with 'schemas' ([e200115](https://github.com/omar-dulaimi/prisma-zod-generator/commit/e200115de9a73d43b5dd540c4f48e75d1bc70612)), closes [#118](https://github.com/omar-dulaimi/prisma-zod-generator/issues/118)

## [1.0.3](https://github.com/omar-dulaimi/prisma-zod-generator/compare/v1.0.2...v1.0.3) (2025-07-22)

### 🐛 Bug Fixes

* resolve TypeScript inference issues with z.lazy() relations ([6da8eb8](https://github.com/omar-dulaimi/prisma-zod-generator/commit/6da8eb800d3610da52f022146d9448d963111ec1))

### 📚 Documentation

* remove hardcoded version numbers from README ([95d6cbd](https://github.com/omar-dulaimi/prisma-zod-generator/commit/95d6cbdb08fd6fd897ee0e0f99ada71c9fbe8a1f))

## [1.0.2](https://github.com/omar-dulaimi/prisma-zod-generator/compare/v1.0.1...v1.0.2) (2025-07-22)

### 🐛 Bug Fixes

* resolve schema compilation errors in Issue [#119](https://github.com/omar-dulaimi/prisma-zod-generator/issues/119) ([3f29b48](https://github.com/omar-dulaimi/prisma-zod-generator/commit/3f29b486a0486b7fa45dff44c1a1b8ca493162e3))
* resolve Vitest worker timeout in CI ([08a5546](https://github.com/omar-dulaimi/prisma-zod-generator/commit/08a5546743bafc5ee16c57f9aaafb8fdb61c069c))

## [1.0.1](https://github.com/omar-dulaimi/prisma-zod-generator/compare/v1.0.0...v1.0.1) (2025-07-22)

### 🐛 Bug Fixes

* remove broken logo image from README ([eb2ba51](https://github.com/omar-dulaimi/prisma-zod-generator/commit/eb2ba51aaed0005b6489de4c8d84f21c6ea4edaf))

### 📚 Documentation

* update README for v1.0.0 stable release ([0f267c9](https://github.com/omar-dulaimi/prisma-zod-generator/commit/0f267c9b7144685530e2a5dd3d3420c9e3e2b5f3))

## 1.0.0 (2025-07-22)

### 🚀 Features

* add comprehensive CI/CD automation and release workflows ([cb562f5](https://github.com/omar-dulaimi/prisma-zod-generator/commit/cb562f5317a1d4d11462c8866dc657cdf780ecab))
* add support for new prisma-client generator ([8224aed](https://github.com/omar-dulaimi/prisma-zod-generator/commit/8224aed0a5ae9a24c76969d655abe9e38e9bafa9)), closes [#116](https://github.com/omar-dulaimi/prisma-zod-generator/issues/116)
* configure semantic-release for beta releases from upgrade branch ([6dfdd98](https://github.com/omar-dulaimi/prisma-zod-generator/commit/6dfdd9885b5f4e295427256d92e0f7f26095cfd2))
* enable semantic-release for upgrade branch ([d6ef9b3](https://github.com/omar-dulaimi/prisma-zod-generator/commit/d6ef9b3fd4e8f3515cdddffbc3ab955a61b21e1a))
* remove strict requiresGenerators constraint ([6e1d41b](https://github.com/omar-dulaimi/prisma-zod-generator/commit/6e1d41b613145a1bd535f23140ca738cc5cce2d5)), closes [#116](https://github.com/omar-dulaimi/prisma-zod-generator/issues/116)

### 🐛 Bug Fixes

* add MongoDB schema generation step to CI workflow ([b120f12](https://github.com/omar-dulaimi/prisma-zod-generator/commit/b120f127ee39681faeb0632bc06b14754966ff64))
* add skipDuplicates option to createMany query ([710d522](https://github.com/omar-dulaimi/prisma-zod-generator/commit/710d52215b0c5c4e0f026a2e52fdfe8864085179))
* adjust MongoDB test expectations for CI compatibility ([0c53f60](https://github.com/omar-dulaimi/prisma-zod-generator/commit/0c53f6075f481973eb9d9ff3a30018386a678659))
* adjust provider discovery test and fix more ESLint issues ([bb83e97](https://github.com/omar-dulaimi/prisma-zod-generator/commit/bb83e97c19aa0d54b0b2788cbea1679f15f1b553))
* adjust test expectations and resolve remaining ESLint issues ([d1ae46e](https://github.com/omar-dulaimi/prisma-zod-generator/commit/d1ae46e7bd7d862020437b9956ff123b139b549f))
* convert vitest config to JavaScript for better Node 18 compatibility ([0106c4f](https://github.com/omar-dulaimi/prisma-zod-generator/commit/0106c4f4f3ead2c16d4432ece73eeef481ccc2ce))
* correct branch references from main to master in CI/CD workflows ([009aa79](https://github.com/omar-dulaimi/prisma-zod-generator/commit/009aa79c2312e78a35d342398ab3b5bcddd0ed3f))
* no array around createManyInput ([a244cac](https://github.com/omar-dulaimi/prisma-zod-generator/commit/a244cac1f0475f77948c49c5efec328c59aa8060))
* prevent NaN errors in MongoDB test success rate calculations ([1498a80](https://github.com/omar-dulaimi/prisma-zod-generator/commit/1498a80565ffb9b306e271d3a069d0ffda494853))
* replace absolute paths with relative paths in provider schemas ([97cb362](https://github.com/omar-dulaimi/prisma-zod-generator/commit/97cb36215245966369c20ab1e29f1b970206f8a7))
* resolve all remaining ESLint any type warnings ([b26ea59](https://github.com/omar-dulaimi/prisma-zod-generator/commit/b26ea593d7e4663908be5e70d58d1f73cccd6621))
* resolve CI test failures and ESLint issues ([89ba9e6](https://github.com/omar-dulaimi/prisma-zod-generator/commit/89ba9e60dd8f6f741d3d1725821ef12b2e2c4a94))
* resolve ESLint configuration and CI issues ([df52348](https://github.com/omar-dulaimi/prisma-zod-generator/commit/df5234862e18583f26643c93eb38acf9d2773e82))
* resolve MongoDB schema coverage test import issues ([989addd](https://github.com/omar-dulaimi/prisma-zod-generator/commit/989addd452df84fed45e6f530bdeeb6cbd6bace2))
* skip vitest tests for Node 18 due to Vite 7.x requirements ([93605e1](https://github.com/omar-dulaimi/prisma-zod-generator/commit/93605e1fb361597bac1191c1371f08d3f6a8c453))
* update dependabot configuration ([d5f57fb](https://github.com/omar-dulaimi/prisma-zod-generator/commit/d5f57fb36a28698861cfb23ee95c0f6efe5d985f))
* update package-lock.json with semantic-release dependencies ([814be64](https://github.com/omar-dulaimi/prisma-zod-generator/commit/814be64def5b449fec7b3bab9d4192dc3361f0ec))
* update vitest config for v3 compatibility with Node 18 ([7f34eab](https://github.com/omar-dulaimi/prisma-zod-generator/commit/7f34eab86040ef99ba89c4455a11cf84f9fadf8e))
* use correct DMMF namespace import alias ([a495445](https://github.com/omar-dulaimi/prisma-zod-generator/commit/a495445e6a943db2b750d0ddb082add4d491ce10))

### 📚 Documentation

* add beta testing announcement to README ([1b0bfb2](https://github.com/omar-dulaimi/prisma-zod-generator/commit/1b0bfb20fefecf32674f45a9e00bfc8158254d4d))
* add comprehensive CI/CD workflow usage guide ([3da4f92](https://github.com/omar-dulaimi/prisma-zod-generator/commit/3da4f921f7ef55533d259844c9102e6acac0e962))
* add prominent support section to README ([0803dc3](https://github.com/omar-dulaimi/prisma-zod-generator/commit/0803dc3a094fd69f8c1173de489d2c01b9d9831e))
* clarify GitHub secrets setup for repository vs environment secrets ([c8ea5cc](https://github.com/omar-dulaimi/prisma-zod-generator/commit/c8ea5cc8eafd7860e4df8d3b56ba74ca8a735c03))
* clarify test schema purpose for new generator ([659c4e0](https://github.com/omar-dulaimi/prisma-zod-generator/commit/659c4e0a113eeb0b23179dcb3aa1e97c0fff7a71))
* comprehensive README improvements ([9d014b9](https://github.com/omar-dulaimi/prisma-zod-generator/commit/9d014b940c1c21e8afc3714736f3f7d539393a2d))
* correct link in table of contents ([918f862](https://github.com/omar-dulaimi/prisma-zod-generator/commit/918f8628d89bcccf5d98003598008dfb35afa09a))
* focus beta announcement on Prisma 6 & Zod 4 compatibility ([087c257](https://github.com/omar-dulaimi/prisma-zod-generator/commit/087c25734b7560e04488764342cadfea37c61129))
* improve NPM token setup instructions and troubleshooting ([8f379f9](https://github.com/omar-dulaimi/prisma-zod-generator/commit/8f379f9b7fe8890117830ca102267225c9527145))
* modernize README with enhanced styling and comprehensive content ([1f226a1](https://github.com/omar-dulaimi/prisma-zod-generator/commit/1f226a163ce9676c2aa5a1316faa1283607a9da5))
* update README for Prisma 6 and Zod 4 support ([bdac9dd](https://github.com/omar-dulaimi/prisma-zod-generator/commit/bdac9ddbd3e2956031eed3422a36c7d3812d5d72))
* update to v0.8.15-beta.0 with new generator support ([7372825](https://github.com/omar-dulaimi/prisma-zod-generator/commit/7372825e797d47b87d155a7b78c08b62fd380bed))

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Comprehensive CI/CD pipeline with GitHub Actions
- Automated release workflow with semantic versioning
- Multi-provider database testing infrastructure
- Extended test matrix for cross-platform compatibility
- Dependabot configuration for automated dependency updates
- Semantic release configuration for automated changelog generation

### Changed
- Improved test command reliability and compatibility
- Updated ESLint configuration for better TypeScript support
- Enhanced vitest configuration for better performance

### Fixed
- Test command compatibility issues with Zod v4
- Undefined config errors in multi-provider tests
- TypeScript type checking configuration

---

*This changelog is automatically generated using [semantic-release](https://github.com/semantic-release/semantic-release).*
