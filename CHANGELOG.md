# Changelog

All notable changes to this project are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- A "Powered by Love Letter" link below the `FeedbackSheet` submit button,
  opening https://amirhayek.dev/LoveLetter/.

### Changed

- **BREAKING:** renamed the project from AppFeedback to **Love Letter**.
  Kotlin packages moved from `com.appfeedback.*` to `com.loveletter.*`
  (`com.loveletter.core`, `com.loveletter.android`); Maven artifacts are now
  `io.github.hayek:loveletter-android` and
  `io.github.hayek:loveletter-android-compose` (were `appfeedback-android` /
  `appfeedback-android-compose`); the sample app's namespace/applicationId is
  `com.loveletter.sample`. The repository moved to
  `github.com/hayek/loveletter-android`, the spec to `hayek/loveletter-spec`, and
  the docs to <https://hayek.github.io/loveletter-docs/>. The issue-body wire
  format is unchanged. Update your imports and dependency coordinates.

### Fixed
