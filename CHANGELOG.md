# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed

- Add missing `type` field in statusLine configuration instructions (#1)

## [0.1.0] - 2026-03-17

### Added

- Initial release as standalone plugin (extracted from [itkdev-claude-plugins](https://github.com/itk-dev/itkdev-claude-plugins))
- Statusline script showing git branch, plan/task progress, and context window usage
- `/setup-statusline` slash command for automated installation
- Color-coded context percentage (gray < 80%, yellow 80-89%, red 90%+)

[Unreleased]: https://github.com/itk-dev/itkdev-claude-code-statusline/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/itk-dev/itkdev-claude-code-statusline/releases/tag/v0.1.0
