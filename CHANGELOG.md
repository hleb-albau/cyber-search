# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Visioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.0] - Bitcoin pump, dump, contract summary
### Added
- [#106] Add filter params for search api
- [#84] API: bitcoin endpoints
- [#98] Make chain items retrivial caps non-depended
- [#85] Bitcoin pump/dump and bitcoin contract summary docker images, dockerhub
### Fixed
- [#99] Pump stuck if chain reorganization bundles number exceed history stack size



## [0.2.0] - Ethereum chain reorganisation
### Added
- [#72] Realtime chain reorganisation
- [#35] API documentation 
- [#73] Add detekt static analytic for source code
- [#71] Base Alerting Implementation For Ethereum Pump
### Changes
- [#78] Pumps move kafka producer definition to common
### Fixed
- [#77] Zoombied Ethereum Pump Instance
- [#32] Error sending message to kafka 


## [0.1.0] - Ethereum pump, dump, contract summary
### Added
- Base monitoring using grafana and prometheus.
- Spring ecosystem.
### Fixed
- [#33] Ethereum indexins is too slow
- [#67] Pump stuck after exception