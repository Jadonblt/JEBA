# Changelog

All notable changes to this project are recorded here. Before making further changes, review this file and update the version number.

## [0.2.0] - 2026-07-24

### Fixed
- Prevented the app from crashing when an extremely large rounds value is entered.
- Added JavaScript validation and clamping so HTML limits cannot be bypassed.
- Added handling for empty, non-numeric, decimal, and out-of-range values.

### Changed
- Maximum rounds increased to 200.
- Warm-up maximum increased to 60 minutes.
- Fast-pedal maximum increased to 3,600 seconds (60 minutes).
- Recovery maximum increased to 3,600 seconds (60 minutes).
- Cool-down maximum increased to 60 minutes.
- Added visible version number v0.2.0 to the app and document title.
- Added an inline validation message when a value is corrected.

## [0.1.0] - Initial prototype

### Added
- Beginner, HIIT, and Endurance presets.
- Custom warm-up, fast-pedal, recovery, rounds, and cool-down settings.
- Countdown timer, progress display, sounds, pause, skip, and reset controls.
