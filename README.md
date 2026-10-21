# Mindmappler for Mac

Downloads of Mindmappler, a keyboard-first mapping tool made at Future Memories. This repository only holds the built app; the code lives elsewhere.

## Install

For a Mac with Apple silicon and macOS 13 or later.

1. Download `Mindmappler-x.y.z-arm64.dmg` from the [latest release](https://github.com/FutureMemories/mindmappler-releases/releases/latest), open it, and drag Mindmappler to Applications.
2. Open Mindmappler. The first time, macOS says it couldn't check the app for malware, and doesn't open it. Click Done, or OK (not Move to Trash).
3. Right after that (macOS offers this step only for a while), open System Settings ▸ Privacy & Security, scroll down to "Mindmappler was blocked…", click Open Anyway, and confirm. Mindmappler opens, and from then on it opens like any other app.

macOS asks like this once for every version you download, because the app isn't signed with an Apple Developer ID.

Your first workspace is `~/Mindmappler/Maps`. Keep workspaces in `~/Mindmappler`: for one in Documents, Desktop or iCloud Drive, macOS asks for access again after every update.

## Updates

When a newer version is out, the bottom of the sidebar says so, linking to its release. Download it the same way, quit Mindmappler, drag the new one to Applications to replace the old one, and open it as above.

## Checking a download

Each release's notes list the SHA-256 of its files, which `shasum -a 256 Mindmappler-x.y.z-arm64.dmg` should match.
