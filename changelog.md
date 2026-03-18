# Changelog

All notable changes to **Lift Log** will be documented in this file.

This project follows a structured versioning approach to track feature development, usability improvements, and architectural changes.

---
## [0.7.0] - 2026-03-18
### Added
- New dedicated Changelog page within the Lift Log app
- Navigation from the main page to the Changelog page
- Offline caching support for the changelog page

### Changed
- Lift Log now exposes version history directly in the app UI

### Notes
- This version improves release visibility and gives users an in-app way to review feature history

## [0.6.3] - 2026-03-16
### Added
- Version tracking considerations for UI visibility (manual version awareness)

### Changed
- Improved Archive Review tile readability (contrast adjustments for better legibility)

### Fixed
- Addressed inconsistencies between cached PWA version and deployed GitHub Pages version

### Technical
- Updated service worker cache versioning strategy
- Improved cache invalidation approach to ensure users receive latest updates

---

## [0.6.2] - 2026-03-15
### Changed
- Refined service worker behavior for more predictable update cycles

### Technical
- Adjusted cache naming conventions (e.g., `liftlog-v06-2`)
- Explored dynamic cache busting strategies

---

## [0.6.1] - 2026-03-15
### Fixed
- Initial fixes to Archive Review UI readability
- Minor UI polish across tiles and layout

### Technical
- Began implementing structured cache versioning

---

## [0.6.0] - 2026-03-14
### Added
- Archive system for storing past workouts
- Archive Review interface with tile-based layout
- Ability to revisit historical workout data

### Changed
- Expanded UI to support multi-state navigation (active log vs archive)

### Notes
- First major transition from simple logging → historical tracking
- Introduced increased UI complexity and state management considerations

---

## [0.5.0] - 2026-03-10
### Added
- Progressive Web App (PWA) support
  - `manifest.json`
  - App icons
  - Installability on mobile devices
- Splash screen (minimalist design with Lift Log branding)
- Service worker for offline support

### Changed
- App now launches in standalone mode on mobile
- Improved perceived performance via caching

### Technical
- Initial cache strategy implemented
- Offline-first behavior introduced

### Notes
- Major milestone: transition from webpage → installable app

---

## [0.4.0] - 2026-03-09
### Changed
- Improved mobile usability (iPhone-focused)
- Adjusted tile colors for better contrast
- Improved spacing and touch interaction

### Fixed
- Readability issues on smaller screens

### Notes
- Shift to mobile-first design philosophy
- First version optimized for real gym usage

---

## [0.3.0] - 2026-03-08
### Added
- Improved UI layout for workout entries
- Early tile/card-based design system

### Changed
- Increased readability of logged workouts
- Cleaner visual hierarchy

### Notes
- First usability-focused iteration
- Transition from raw interface → user-friendly design

---

## [0.2.0] - 2026-03-07
### Added
- Structured workout logging system
- Grouping of exercises into sessions

### Changed
- Standardized data model for logs

### Notes
- Established foundational data structure for future features

---

## [0.1.0] - 2026-03-06
### Added
- Initial prototype of workout logging interface
- Basic input fields (exercise, weight, reps)
- Local storage persistence

### Notes
- Proof of concept
- No styling or advanced structure
