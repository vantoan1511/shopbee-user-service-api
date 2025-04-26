# shopbee-user-service-api

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [ 1.1.0 ] - 2025-04-26
### Added
- `tenantId` added as a required parameter for all relevant endpoints.
- `defaultAddress` added as a user's attribute.

### Changed
- Updated schemas for `User` and related objects.
- Modified response structures for several endpoints.

### Removed
- `isDefault` from Address schema.

## [ 1.0.0 ] - 2025-03-22
### Added
- Definition of user operations api.
