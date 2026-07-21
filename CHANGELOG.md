# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## 1.5.0 – 2026-07-21

### Changed

- Bump max Nextcloud version to 35 and use PHP 8.2 in release action @julien-nc
- Update dependencies, fix PHP versions in CI workflows, fix OpenAPI action, apply code style fixes and regenerate OpenAPI specs @julien-nc [#62](https://github.com/nextcloud/approve_links/pull/62)

## 1.4.0 – 2026-03-26

### Added

- Track generated links by ID and usage state, reject reused links, clean up stale links, and improve related tests and error messages (@julien-nc, #31)

### Changed

- Raise the minimum supported PHP and Nextcloud versions, switch Psalm packaging for PHP 8.5 compatibility, and refresh npm dependencies (@julien-nc, #30)
- Remove the unused config controller and routes, and refresh composer and npm dependencies (@julien-nc)

## 1.3.0 – 2025-11-03

### Added

- Support for NC 33

### Changed

- Update npm and composer dependencies

## 1.2.0 – 2025-07-03

### Changed

- Migrate to Vue 3 and nextcloud/vue 9
- Support Nextcloud 32

## 1.1.0 – 2025-01-09

### Changed

- Add support for NC 31
- Update composer and npm dependencies

## 1.0.2 – 2024-08-13

### Added

* The app
