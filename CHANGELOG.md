# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- ## Unreleased -->

# [0.0.4] - 2022-01-27

### Fixed

- Bump @web/test-runner and related deps to resolve issue running tests on Chrome
- Make form-associated tests conditional on the native feature.
- Fixed form-associated custom element definitions (`static formAssociated = true`) when used with the polyfill.
- Fixed patched callback names in form-associated custom element support.
- Fixed handling of mixed-case attributes. Fixes #483

## [0.0.3] - 2021-08-02

- Maintenance release (no user-facing changes)

## [0.0.2] - 2021-06-02

- Fix to allow definition of custom elements whose classes have been created before applying the polyfill.
- Run `connectedCallback` on upgraded elements. Fixes #442.
- Checks if ShadowRoot prototype supports the createElement method to determine if the polyfill should be applied or not.

## [0.0.1] - 2021-02-18

- First public prerelease.