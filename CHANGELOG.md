# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) 
and this project adheres to [Semantic Versioning](http://semver.org/).

## 0.5.0 - 2017-09-22

### Changed

* Changed `MatcherInterface` to allow use callables.
* Updated to `http-interop/http-middleware#0.5`
* Updated phpunit to `^6.0`

## 0.4.0 - 2017-02-29

### Changed

* Replaced container-interop by `psr/container`

## 0.3.0 - 2017-01-28

### Added

* New `Middleland\Matchers\Pattern` to filter by path patterns
* New `Middleland\Matchers\Accept` to filter by Accept headers

### Fixed

* `Middleland\Matchers\Path` compare the directory name, instead the path.

## 0.2.0 - 2017-01-09

### Added

* Support for [container-interop](https://github.com/container-interop/container-interop), to create middleware components on demand

## 0.1.0 - 2017-01-09

First version
