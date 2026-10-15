# Changelog

## [v0.4.0](https://github.com/runapi-ai/kling/releases/tag/v0.4.0) - 2026-10-15

### Changed
- Explain custom and automatic storyboarding, optional sound, and custom shot constraints.

### Removed
- Remove retired model choices from creation metadata and document historical task lookup.
  Migration: Retired models return HTTP 410 for new requests. Query existing task IDs with the original task endpoint; no automatic replacement is applied.


## [v0.3.0](https://github.com/runapi-ai/kling/releases/tag/v0.3.0) - 2026-08-21

### Added
- Document reference-image and source-video editing inputs for Kling V3 Omni.


## [v0.2.16](https://github.com/runapi-ai/kling/releases/tag/v0.2.16) - 2026-08-12

### Changed
- Generate the kling skill from the shared RunAPI recipe with contract-discovered request rules and task behavior, direct local media inputs, complete result verification, and bounded recovery.


## [v0.2.15](https://github.com/runapi-ai/kling/releases/tag/v0.2.15) - 2026-08-10

### Changed
- Complete marketplace distribution for the RunAPI Kling skill.


## [v0.2.14](https://github.com/runapi-ai/kling/releases/tag/v0.2.14) - 2026-07-28

### Added
- Document Kling O1 reference fields, numbered prompt markers, media limits, reference roles, and frame-input restrictions.


## [v0.2.13](https://github.com/runapi-ai/kling/releases/tag/v0.2.13) - 2026-07-23

### Added
- Document Kling 2.6 motion-control inputs, required fields, and model-specific background behavior.


## [v0.2.12](https://github.com/runapi-ai/kling/releases/tag/v0.2.12) - 2026-07-23

### Added
- Document Kling V3 Omni output resolutions, optional sound, final-frame constraints, and the canonical model page.


## [v0.2.11](https://github.com/runapi-ai/kling/releases/tag/v0.2.11) - 2026-07-22

### Added
- Document Kling 2.6 modes, optional sound, final-frame constraints, and the canonical model page.


## [v0.2.10](https://github.com/runapi-ai/kling/releases/tag/v0.2.10) - 2026-07-16

### Changed
- Add Kling V3 Turbo text-to-video and image-to-video model guidance.
- Refresh the Kling variant links for the new catalog pages.

## [v0.2.9](https://github.com/runapi-ai/kling/releases/tag/v0.2.9) - 2026-06-18

### Changed
- Sync skill content with the latest SDK surface

## [v0.2.8](https://github.com/runapi-ai/kling/releases/tag/v0.2.8) - 2026-06-01

### Changed
- Align skill with upstream Input Contract and public API vocabulary changes
- Update endpoint definitions and field constraints

## [v0.2.5](https://github.com/runapi-ai/kling/releases/tag/v0.2.5) - 2026-05-22

Initial release.
