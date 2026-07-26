# Changelog

All notable changes to the Mini Golf Signage project will be documented here.

## [Unreleased]

### Planned

- Day-of-week schedules
- Automatic recovery health check

## [2.0.0] - 2026-07-26

### Added

- Dashboard V2 control center.
- Larger real-time scheduled image previews.
- Live countdowns to the next change.
- Twenty-four-hour schedule timelines.
- Current-time markers on each timeline.
- Global next-change summary.
- Missing-image detection.
- System health reporting.
- Responsive desktop, tablet, and mobile layouts.

### Changed

- Dashboard schedule data refreshes every 30 seconds.
- Countdown timers and timeline markers update locally every second.

## [1.5.0] - 2026-07-26

### Added

- Web-based signage control dashboard.
- Real-time scheduled image previews.
- Regular and holiday schedule status indicators.
- Current and next image information.
- Full-screen and debug-view shortcuts.
- Automatic dashboard refresh every 30 seconds.

## [1.4.0] - 2026-07-26

###Changed

- Improved the reading for the start time in Tab Holiday Overrides

## [1.3.0] - 2026-07-26

### Changed

- Improved image transition to keep the previous image visible underneath.
- Disabled periodic OptiSigns webpage refresh to prevent black-screen flashes.
- Added cache-version support to the OptiSigns URL.

### Fixed

- Fixed brief black flashes during scheduled image transitions.
- Fixed multi-screen URLs displaying a black screen.

## [1.2.0] - 2026-07-26

### Added

- Support for multiple screens using Google Sheet tab names.
- Support for URLs such as `?screen=Arcade`.
- On-screen debugging with `&debug=1`.
- Better error messages for missing images and invalid schedules.

## [1.1.0] - 2026-07-26

### Added

- Google Sheets schedule integration.
- Smooth image fading.
- Automatic image preloading.
- GitHub Pages hosting.
- Google Apps Script schedule feed.

## [1.0.0] - 2026-07-26

### Added

- Initial Mini Golf Signage website.
- Two-image scheduled display.
- OptiSigns Website asset support.
