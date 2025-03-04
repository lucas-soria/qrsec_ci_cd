# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2024-03-03 ([#9](https://github.com/lucas-soria/qrsec_ci_cd/pull/9))
### Changed
- Service versions are configurable.
- README.md command now deleted 'dangling' images when building.
- Changed forwarded headers from frontend to backend.

### Removed
- Useless /admin urls from backend env variables.
- Mongo Express service.
- Port exposed from mongodb.

### Added
- New /auth urls to backend env variables.
- New DB volumes.

## [0.0.3] - 2024-02-13 ([#7](https://github.com/lucas-soria/qrsec_ci_cd/pull/7))
### Added
- CORS configuration as environment variables
- Made version of frontend and backend a variable

## [0.0.2] - 2024-09-28 ([#5](https://github.com/soria-lucas/qrsec_ci_cd/pull/5))
### Added
- Frontend added to docker-compose.yaml.
- Frontend built from multi-stage Dockerfile.
- Cloudflare Tunnel added to docker-compose.yaml.
  - This also provides ssl certificate (allowing the frontend to use the camera).
- Reverse proxy added to docker-compose.yaml.

## [0.0.1] - 2024-02-13 ([#3](https://github.com/soria-lucas/qrsec_ci_cd/pull/3))
### Added
- Backend added to docker-compose.yaml.
- Backend built from multi-stage Dockerfile.

## [0.0.0] - 2023-12-25 ([#1](https://github.com/soria-lucas/qrsec_ci_cd/pull/1))
### Added
- Project's last status.
- CHANGELOG file.   
