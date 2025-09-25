# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [In Development] - Unreleased

## [0.0.23] - 2025-09-25

### Changed
- Replaced has_any_perm with sender_has_any_perm in admin.py

## [0.0.22] - 2025-09-25

### Added
- Added App permissions for better granularity for our usecase.

### Changed

- Changed command permissions to allow for more granularity, force sync has been added to a specific permission
- Changed a number of other permissions to admin_commands to allow non-admin access.
