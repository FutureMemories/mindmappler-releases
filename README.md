# Mindmappler for Mac

Downloads of Mindmappler, a keyboard-first mapping tool made at Future Memories. This repository only holds the built app; the code lives elsewhere.

## Install

For a Mac with Apple silicon and macOS 13 or later.

1. Download `Mindmappler-x.y.z-arm64.dmg` from the [latest release](https://github.com/FutureMemories/mindmappler-releases/releases/latest), open it, and drag Mindmappler to Applications.
2. Open Mindmappler from Applications. macOS checks it once and asks whether to open an app downloaded from the internet: click Open.

The app is signed and notarised by Future Memories AB.

Your first workspace is `~/Mindmappler/Maps`. Keep workspaces in `~/Mindmappler`: for one in Documents, Desktop or iCloud Drive, macOS asks for access again after every update.

## Updates

When a newer version is out, the bottom of the sidebar says so. Click it: Mindmappler downloads the update, shows how far it has come, and restarts into the new version once your changes are saved.

Versions 1.2.0 and earlier weren't signed and can't update themselves: install 1.3.0 or later by hand once (quit Mindmappler, then drag the new one to Applications to replace the old one).

## Checking a download

Each release's notes list the SHA-256 of its files, which `shasum -a 256 Mindmappler-x.y.z-arm64.dmg` should match.
