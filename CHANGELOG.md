# Changelog

## v1.0.1 - 2026-05-10

### Fixed

- Removed unresolved merge conflict markers from the FastAPI app startup file that caused the published Docker image to fail with a `SyntaxError` on boot.
- Removed unresolved merge conflict markers from the frontend sidebar version display.

## v1.0.0 - 2026-03-21

### Added

- Initial stable release of Brisa.
- Docker-based fan control service for TrueNAS SCALE and Linux hosts.
- Support for liquidctl USB fan controllers and hwmon PWM fan headers.
- Web UI, REST API, Prometheus metrics, virtual sensors, dashboard groups, card colors, and SQLite history.
