# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

### Fixed

### Changed

### Removed

## [1.1.0]

### Added

### Fixed

* Fixed `BOOT` button that was not wired to the microcontroller [#1](https://github.com/Calebe94/appa-pcb/issues/1);
* Fixed `COL_10` and `COL_11` that was not wired to the microcontroller [#2](https://github.com/Calebe94/appa-pcb/issues/2); 
* Added `res/appa-schematic.svg` file;

### Changed

### Removed

* Removed `appa.jpg` file because there is already a schematic file in the `res/` folder;
* Removed `fp-info-cache` file;
* Removed `gerber/` folder;

## [1.0.1]

### Added

* Added `.github` folder with [Github Templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository);

### Fixed

### Changed

* Updated changelog;

### Removed

## [1.0.0]

### Added

* Added schematic as a `.svg` image;
* Added GPL3+ license file;
* Added Appa and my logo as silk;
* Added the `gerber` folder to ship the gerber files on tags;
* Added GPL3+ license logo as silk;
* Added `ATMEGA328p` standalone circuit as a redundancy;
* Added `gerber/` folder;
* Added `GPL3.svg` logo;
* Added `fp-info-cache` file;

### Fixed

### Changed

* Updated readme with some relevant informations;
* Changed switches layout to be read from left to right on the PCB;

### Removed

[unreleased]: https://github.com/Calebe94/appa-pcb/compare/1.1.0...HEAD
[1.1.0]: https://github.com/Calebe94/appa-pcb/compare/1.0.1...1.1.0
[1.0.1]: https://github.com/Calebe94/appa-pcb/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/Calebe94/appa-pcb/releases/tag/1.0.0
