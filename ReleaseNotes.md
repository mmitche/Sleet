# Release Notes

## 2.2.0
* Fix for multiple catalog pages
* Sleet versions of the same semantic version patch will no longer require upgrading the feed to work together.

## 2.1.0
* Fix for race condition when reading symbols files
* Props path fix
* Improved exists check performance

## 2.0.0
* Improved console output progress display.
* Performance improvements, files are committed to the feed in parallel which cuts push time in half for some scenarios.
* Symbols feed support, symbols packages will be stored in the feed and dll and pdb files will be available for debuggers.
* Catalog is disabled by default, this improves perf for feeds which overwrite packages.
* Invalid command arguments now return a non-zero exit code.
* Adds package details from the catalog to the registration package details page when the catalog is disabled.
* Moved from netstandard1.3 to netstandard2.0
