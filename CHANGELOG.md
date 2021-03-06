# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---
## Version 1.12.21, 1/2/2020

### Added

AsyncHttpRequest is a convenient class to read HTTP events from the rest-automation app.

### Removed

N/A

### Changed

N/A

---
## Version 1.12.17, 12/16/2019

### Added

1. get_route() method is added to PostOffice so that current service can retrieve its own route name
2. The route name of the current service is added to an outgoing event when the "from" field is not present

### Removed

N/A

### Changed

N/A

---
## Version 1.12.12, 10/26/2019

Sync up version number with main mercury project to support multi-tenancy for event streams.

### Added

N/A

### Removed

N/A

### Changed

N/A

---
## Version 1.12.9, 8/27/2019

Sync up version number with main mercury project

### Added

Distributed tracing feature

### Removed

N/A

### Changed

language pack API key obtained from environment variable

---
## Version 1.12.8, 8/15/2019

Sync up version number with main mercury project

### Added

N/A

### Removed

N/A

### Changed

N/A

---
## Version 1.12.7, 7/15/2019

Support discovery of multiple route in the updated `po.exists` API

### Added

N/A

### Removed

N/A

### Changed

N/A

---

## Version 1.12.4, 6/24/2019

### Added

1. Store-n-forward pub/sub API will be automatically enabled if the underlying cloud connector supports it. e.g. kafka
2. ObjectStreamIO, a convenient wrapper class, to provide event stream I/O API.
3. Object stream feature is now a standard feature instead of optional.
4. Deferred delivery example in demo.py
5. Add inactivity expiry timer to ObjectStreamIO so that house-keeper can clean up resources that are idle

### Removed

N/A

### Changed

Bug fix - update EventEnvelope with missing field "extra" which is used as additional routing information for language packs.
This allows correct RPC routing between python applications via the language connector.

---

## Version 1.11.40, 4/29/2019

### Added

Version number sync up with main Mercury project.

### Removed

N/A

### Changed

N/A

---

## Version 1.11.39, 4/29/2019

### Added

First release. Version number sync up with main Mercury project.

### Removed

N/A

### Changed

N/A
