# Changelog

## [v0.0.6]

### Added

- Support for UNIF ROMs (`.unf` / `.unif`).

### Changed

- Nothing.

### Fixed

- Oversized ROMs are refused when `size > flash_cache_usable_size()` (same
  ABI helper as gngeo), with a dialog showing ROM size vs flash cache max.

### Install

- Unzip the release archive onto the SD card root (`cores/fceumm.bin`).
- Place ROMs/FDS/NSF/UNIF under `/roms/nes/` (extensions: `nes ines fds nsf unf unif`).
- Place FDS bios under `/bios/nes/disksys.rom` to play FDS games.
- Requires firmware whose ABI matches `SDK_VERSION` in this repository.
