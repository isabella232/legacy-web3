# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2020-11-20

### Fixed

- **(IMPORTANT)** Fixed `window.web3` overwrite behavior ([#18](https://github.com/MetaMask/legacy-web3/pull/18))
  - While MetaMask will stop injecting `web3`, it will continue to inject a shim at `window.web3` to preserve the `web3.currentProvider` property.
  To accomplish this, the overwrite behavior had to be updated.
  Previous version of this package will not work and are deprecated.

## [1.0.2] - DEPRECATED

## [1.0.1] - DEPRECATED

## [1.0.0] - DEPRECATED

[Unreleased]:https://github.com/MetaMask/legacy-web3/compare/v1.1.0...HEAD
[1.1.0]:https://github.com/MetaMask/legacy-web3/compare/v1.0.2...v1.1.0
[1.0.2]:https://github.com/MetaMask/legacy-web3/compare/v1.0.1...v1.0.2
[1.0.1]:https://github.com/MetaMask/legacy-web3/compare/v1.0.0...v1.0.1
