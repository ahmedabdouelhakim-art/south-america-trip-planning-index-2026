# Changelog

All notable changes to the South America Trip Planning Index are documented in
this file. Dates use the ISO 8601 format `YYYY-MM-DD`.

## [1.1] - 2026-08-02

### Added

- Stable source IDs and explicit source-reference columns for each country row.
- Review controls: `checked_on`, `next_review_due`, and source sensitivity.
- Separate minimum, maximum, and buffer-day planning fields.
- Dedicated metadata, citation, license, and 1200 x 630 cover files.
- Archival release on Zenodo with version DOI
  [`10.5281/zenodo.21765168`](https://doi.org/10.5281/zenodo.21765168) and
  concept DOI [`10.5281/zenodo.21765167`](https://doi.org/10.5281/zenodo.21765167).

### Changed

- Expanded the country table from 13 to 27 fields while retaining all 12
  sovereign South American countries.
- Normalized the 44-row source registry from 7 to 14 fields.
- Separated editorial judgments from source-supported claims more explicitly.

### GitHub mirror documentation sync - 2026-08-03

- Added the assigned Zenodo DOI to `README.md`, `CITATION.cff`, and
  `LICENSE.md`.
- Added repository navigation, a quick-start example, validation results, and
  an integrity manifest.
- Kept both CSV files, the metadata text, and the release cover byte-for-byte
  identical to the archived Version 1.1 files.

## [1.0] - 2026-08-02

### Added

- Initial 12-country planning table.
- Initial 44-record source register.

[1.1]: https://doi.org/10.5281/zenodo.21765168
[1.0]: https://visaadvisor.ai/south-america-travel-planning-index-2026/
