# Changelog

## [Unreleased]

### Breaking Change
- [DAE-113](https://coveod.atlassian.net/browse/DAE-113) — Deprecated the /api/v1 endpoints. All users must migrate to /api/v2 by October 1st, 2025. ([#70](https://github.com/malratta-coveo/test/pull/70))

### Improved
- [DAE-113](https://coveod.atlassian.net/browse/DAE-113) — The user interface for mobile devices is now more responsive and easier to navigate. ([#70](https://github.com/malratta-coveo/test/pull/70))
- [DAE-114](https://coveod.atlassian.net/browse/DAE-114) — Enhanced error messaging for API authentication failures to be more descriptive. ([#71](https://github.com/malratta-coveo/test/pull/71))
- [DAE-114](https://coveod.atlassian.net/browse/DAE-114) — Enhanced error messaging for API authentication failures to be more descriptive. ([#73](https://github.com/malratta-coveo/test/pull/73))

### Fixed
- [DAE-114](https://coveod.atlassian.net/browse/DAE-114) — Patched a memory leak in the data processing service that caused intermittent crashes. ([#71](https://github.com/malratta-coveo/test/pull/71))
- [DAE-114](https://coveod.atlassian.net/browse/DAE-114) — Patched a memory leak in the data processing service that caused intermittent crashes. ([#73](https://github.com/malratta-coveo/test/pull/73))

## [2025-01-01]

### Breaking Change
- [DAE-111](https://coveod.atlassian.net/browse/DAE-111) — Renamed user_profiles.userId column to user_profiles.user_id for consistency. ([#68](https://github.com/malratta-coveo/test/pull/68))

### Improved
- [DAE-112](https://coveod.atlassian.net/browse/DAE-112) — Optimized database query for the main analytics dashboard, reducing load times by an average of 40%. ([#69](https://github.com/malratta-coveo/test/pull/69))

### Added
- [DAE-111](https://coveod.atlassian.net/browse/DAE-111) — New endpoint /api/v2/reports/export for CSV data exports. ([#68](https://github.com/malratta-coveo/test/pull/68))
- [DAE-112](https://coveod.atlassian.net/browse/DAE-112) — last_login_ip column to the users table to enhance security auditing capabilities. ([#69](https://github.com/malratta-coveo/test/pull/69))

### Fixed
- [DAE-111](https://coveod.atlassian.net/browse/DAE-111) — Resolved an issue where date filters in the dashboard were not applying correctly in the CET time zone. ([#68](https://github.com/malratta-coveo/test/pull/68))
- [DAE-112](https://coveod.atlassian.net/browse/DAE-112) — Corrected a calculation error in the monthly_recurring_revenue summary metric. ([#69](https://github.com/malratta-coveo/test/pull/69))
