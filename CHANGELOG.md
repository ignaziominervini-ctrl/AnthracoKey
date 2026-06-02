# Changelog

All notable changes to AnthracoKey are documented here.
This project follows simple incremental versioning (v0.9-beta → v1.0, v1.1, ...).

## [v0.9-beta] - 2026-06-02

First public release — **development version**.
Validated on synthetic data; empirical validation on real charcoal datasets in
progress. Published to obtain a citable, date-stamped DOI ahead of a stable v1.0.

### Features
- Import of AnthracoForm determination CSVs
- Empirical IAWA anatomical feature profiles computed per taxon
- Region- (assemblage-) specific dichotomous key construction via a greedy
  feature-selection algorithm
- Interactive key navigation (portable JSON, no browser storage required)
- Plain-text key export for papers and reports
- Fully offline operation, no dependencies

### Known limitations
- Empirical validation on real datasets not yet completed
- Keys reflect the completeness and accuracy of the input reference profiles

<!--
Template for future entries — copy this block when you make a new release:

## [v1.0] - YYYY-MM-DD

### Added
- ...

### Changed
- ...

### Fixed
- ...
-->
