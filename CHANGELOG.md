# Changelog

## [Unreleased]

### Breaking Change
- [JIRA-1111](Link1) — Deprecated the /api/v1 endpoints. All users must migrate to /api/v2 by October 1st, 2025. ([#70](https://github.com/malratta-coveo/test/pull/70))

### Improved
- [JIRA-1111](JIRA-1111) — The user interface for mobile devices is now more responsive and easier to navigate. ([#70](https://github.com/malratta-coveo/test/pull/70))
- [JIRA-1111](JIRA-1111) — Enhanced error messaging for API authentication failures to be more descriptive. ([#71](https://github.com/malratta-coveo/test/pull/71))
- [JIRA-1111](JIRA-1111) — Enhanced error messaging for API authentication failures to be more descriptive. ([#73](https://github.com/malratta-coveo/test/pull/73))

### Fixed
- [JIRA-1111](JIRA-1111) — Patched a memory leak in the data processing service that caused intermittent crashes. ([#71](https://github.com/malratta-coveo/test/pull/71))
- [JIRA-1111](JIRA-1111) — Patched a memory leak in the data processing service that caused intermittent crashes. ([#73](https://github.com/malratta-coveo/test/pull/73))

## [2025-01-01]

### Breaking Change
- [JIRA-1111](JIRA-1111) — Renamed user_profiles.userId column to user_profiles.user_id for consistency. ([#68](https://github.com/malratta-coveo/test/pull/68))

### Improved
- [JIRA-1111](JIRA-1111) — Optimized database query for the main analytics dashboard, reducing load times by an average of 40%. ([#69](https://github.com/malratta-coveo/test/pull/69))


### Fixed
- [JIRA-1111](JIRA-1111) — Resolved an issue where date filters in the dashboard were not applying correctly in the CET time zone. ([#68](https://github.com/malratta-coveo/test/pull/68))
- [JIRA-1111](JIRA-1111) — Corrected a calculation error in the monthly_recurring_revenue summary metric. ([#69](https://github.com/malratta-coveo/test/pull/69))
