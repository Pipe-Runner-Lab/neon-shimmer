# Change Log

All notable changes to the "Neon Shimmer" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

### Added

- New theme: **Neon Shimmer (Crimson Drive)** — Intense deep red UI and #E64471 primary mapping
- New theme: **Neon Shimmer (Bubblegum Punk)** — Vivid pink/magenta dominance with soft lavender strings
- Updated terminal ANSI colors, git decorations, notification icons, and merge conflicts to use the neon palette rather than VS Code defaults
- Added UI support for modern features: bracket pair colorization, inlay hints, sticky scroll, command center, and keybinding labels
- Added `editorStickyScroll.border`, `tab.lastPinnedBorder`, `sash.hoverBorder` UI color tokens
- Added automated GitHub release workflow on tag push

### Fixed

- Added missing `debugConsole` colors to fix invisible output text
- Replaced off-palette error reds with the theme's official red (`#ff1c5b`)
- Fixed invisible `editorInfo` squiggles and background highlights
- Fixed leading space in `meta.brace.square` scope that prevented proper matching
- Fixed mislabeled `"support php constants"` rule that actually targeted Rust scopes
- Renamed duplicate token names for clarity (java, classes, constants, support types)

### Changed

- Updated `devDependencies` from deprecated `vsce` to `@vscode/vsce`
- Improved `.vscodeignore` to exclude unnecessary files from packaging

## [1.0.2]

### Updates

- Fixed background selection color for terminal
- Updated screenshots
