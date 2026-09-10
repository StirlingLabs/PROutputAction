# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)

## [4.0.0] - 10.08.2026

### Infrastructure
- Runtime: `action.yml` now uses `node24`; `.nvmrc `bumped to `v24`
- Dependency removal: dropped the `glob` package in favour of the built-in `node:fs/promises`
	- 	With new tests
- Updated multiple packages and actions
- Rebuild the action (~7k lines smaller, mostly from dropping glob)
- Moved `test.yml` to the correct directory `.github/workflows`
- Changed ownership to @zattoo/chapter-technology-frontend

## [3.0.1] - 25.07.2025

## Fixed
- [FE-1483](https://zattoo2.atlassian.net/browse/FE-1483) Fix crash when PR description is empty

## [3.0.0] - 10.05.2023

### Infrastructure
- Upgrade to node `20`
- Updated dependencies
- Added typescript check
- Added jest types
- Replaced `@zeit/ncc` for `@vercel/ncc`

## [2.0.0] - 02.09.2022

## Added
- Unique name for each output entity
- Option to position content on top of the pull-request description

## [1.0.1] - 23.08.2022

## Fixed
- [WEBCORE-121](https://zattoo2.atlassian.net/browse/WEBCORE-121) Fix i18n output in GitHub PR description

## [1.0.0] - 18.11.2020

### Added
- Initial Functionality
