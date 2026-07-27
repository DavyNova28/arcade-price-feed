# Changelog

All notable changes to Mini Golf Signage Manager are recorded here.

## [1.0.0] — Stable Candidate

### Added

- Schedule Manager
- Daily Schedule Calendar
- Holiday Overrides and Holiday Calendar
- GitHub Image Library and generated image index
- Backup and restore
- Audit log
- Offline dashboard snapshots
- Apps Script telemetry
- Automatic service checks
- Health score
- Player heartbeat
- Player version compliance
- Go-Live Readiness
- Controlled Rollout Assistant
- Rollout progress tracking
- Light and dark themes

### Improved

- Apps Script schedule caching
- Staggered player polling
- Quiet-hours behavior
- Image filename capitalization handling
- System Health full-width layout
- Offline-state readability
- Health score calibration

### Fixed

- Stale telemetry errors
- `Schedule` fallback-tab confusion
- Calendar event overflow
- Image-browser search and close controls
- Player version refresh and preflight controls
- JavaScript accidentally inserted into CSS during development

### Architecture

- Split the dashboard into separate HTML, CSS, and JavaScript files.
