<!-- CHANGELOG.md — Version history for the uitdl-authoring skill. -->

# Changelog

## 1.0.1 — 2026-10-17

- Clarified that `waits` represents the user remaining in a UI until an observable completion, timeout, or expiration changes the UI.
- Clarified that loading begins through the initiating user action and that a blocking loading modal is a separate UI whose completion `waits` transition leads to the loaded destination.
- Added a canonical loading-modal example and prohibited ambiguous start-of-loading phrases such as `waits "data loading"`.

## 1.0.0 — 2026-10-17

- Added a canonical SemVer field to `SKILL.md`.
- Added version increment rules and consistency checks for future skill and reference updates.
