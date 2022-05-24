# Persistent Data System Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## Unreleased

## [1.0.3] - 2022-05-24

### Added
- Move previous saved data file before saving new data

### Fixed
- Use Assets/Resources folder instead of package folder to update datalist, previous folder was locked for packages
- prefill data name of saved data from type full name

## [1.0.2] - 2022-04-06

### Fixed
- Auto dependencies in package

## [1.0.1] - 2021-10-13

### Added
- New event onPlayerDataLoaded

## [1.0.0] - 2021-10-12

### Fixed
- Find and load the correct assembly for the children of SavedData classes to load
- Editor assembly restricted to Editor platform

### Added
- First publish of this new package: a system to load and save persistent data like default player values, player saves, etc.

### Changed

### Deprecated

### Removed

### Fixed

### Security
