# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## 1.2.1 - 2020-03-14

### Fixed

- Scope internal collection to the current group to avoid dots in keys

## 1.2.0 - 2020-03-14

### Added

- Implemented `ArrayAccess#offsetGet`
- Implemented `ArrayAccess#offsetExists`
- Implemented `ArrayAccess#offsetSet`
- Implemented `ArrayAccess#offsetUnset`

## 1.1.0 - 2020-03-14

### Added

- Implemented `Arrayable#toArray`
- Implemented `Jsonable#toJson`
- Implemented `JsonSerializable#jsonSerialize`
- Implemented `Countable#count`
- Implemented `IteratorAggregate#getIterator`

### Changed

- Make the `value` column `nullable`

## 1.0.0 - 2020-03-14

- initial release

[Unreleased]: https://github.com/kodekeep/laravel-meta-attributes/compare/master...develop
