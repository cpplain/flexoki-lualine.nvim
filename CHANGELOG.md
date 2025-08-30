# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

### Changed

- **Improved contrast** - Enhanced visibility and readability across all lualine modes:
  - Mode indicators now use higher contrast color variants (blue3, green3, magenta3, red3, orange3)
  - Statusline text upgraded from tx2 to tx for better foreground contrast
  - Background sections changed from bg to ui for improved section separation

### Deprecated

### Removed

### Fixed

### Security

## [0.1.0] - 2025-08-23

### Added

- **Initial release** - Extracted lualine theme from flexoki.nvim into dedicated plugin
- **Complete lualine theme** - Support for all lualine modes:
  - Normal mode with blue accent
  - Insert mode with green accent
  - Visual mode with magenta accent
  - Replace mode with red accent
  - Command mode with orange accent
  - Terminal mode with green accent
  - Inactive window styling with muted colors
- **Flexoki color integration** - Uses colors from cpplain/flexoki.nvim for consistency
- **Automatic theme switching** - Adapts to light/dark background changes
- **Documentation** - Complete setup and usage examples

[unreleased]: https://github.com/cpplain/flexoki-lualine.nvim/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/cpplain/flexoki-lualine.nvim/releases/tag/v0.1.0
