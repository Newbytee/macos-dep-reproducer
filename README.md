# macos-dep-reproducer

This repository reproduces a bug in flatpak-poetry-generator where macOS wheels
may be picked despite macOS binaries not working on Linux.

Issue: https://github.com/flatpak/flatpak-builder-tools/issues/394
