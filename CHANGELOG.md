# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog],
and this project adheres to [Semantic Versioning].

## [Unreleased]

- /

## [1.4.0] - 2024-01-16

### Added

- Button Click Counter: Implemented a new feature to increment the
  counter exclusively when a specific button (identified by
  data-testid="send-button") is clicked.

### Removed

- Removed Key Press Detection: Disabled the functionality to increment
  the counter on pressing the Enter key. This was achieved by removing
  the handleKeyup function and its corresponding event listener.

### Changed

- Simplified Click Handler (handleClick): Streamlined the handleClick
  function to focus solely on detecting clicks on the specified button
  and incrementing the counter accordingly.

<!-- Links -->
[keep a changelog]: https://keepachangelog.com/en/1.0.0/
[semantic versioning]: https://semver.org/spec/v2.0.0.html

<!-- Versions -->
[unreleased]: https://github.com/lundeen-bryan/ChatGPT-Counter/compare/v0.0.2...HEAD
[1.4.0]: https://github.com/lundeen-bryan/ChatGPT-Counter/releases/tag/v1.4.0