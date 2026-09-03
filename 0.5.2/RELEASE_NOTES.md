# CineRename 0.5.2

CineRename 0.5.2 is the current stable release for movie, TV and anime library cleanup, bulk renaming and NAS/server use.

## Download

Recommended installers:

- [Windows x64 installer (.exe)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/CineRename_0.5.2_x64-setup.exe) (8.6 MB)
- [Windows x64 installer (.msi)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/CineRename_0.5.2_x64_en-US.msi) (11.9 MB)
- [macOS Apple Silicon (.dmg)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/CineRename_0.5.2_aarch64.dmg) (12.3 MB)
- [macOS Intel (.dmg)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/CineRename_0.5.2_x64.dmg) (13.1 MB)
- [Linux x64 AppImage](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/CineRename_0.5.2_amd64.AppImage) (83.2 MB)
- [Linux x64 .deb](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/CineRename_0.5.2_amd64.deb) (12.5 MB)
- [Linux x64 .rpm](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/CineRename-0.5.2-1.x86_64.rpm) (12.5 MB)

Server and NAS builds:

- [NAS / server Linux x64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/CineRename_0.5.2_nas_linux_x86_64.tar.xz) (13.6 MB)
- [NAS / server Linux arm64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/CineRename_0.5.2_nas_linux_aarch64.tar.xz) (12.3 MB)
- [Docker archive x64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/CineRename_0.5.2_docker_linux_amd64.tar.gz) (68.1 MB)
- [Docker archive arm64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/CineRename_0.5.2_docker_linux_arm64.tar.gz) (65.6 MB)

You can also open the [release page](https://github.com/CineRename/CineRename-Releases/releases/tag/v0.5.2) for the complete asset list.
Full installation and usage docs are available at [cinerename.app/docs](https://cinerename.app/docs/).

## Highlights

- Makes watched folders fully resilient: disconnected drives or missing paths no longer block watcher startup or folder management.
- Eliminates infinite subtitle re-import loops across manual downloads, Automatic Mode, and sidecar renames.
- Improves background ergonomics: newly detected media no longer steals screen focus or closes open review dialogs.
- Resolves the infinite loading spinner and close button issue in the subtitle preview dialog.
- Enhances Studio toolbar readability with granular batch status counters and perfectly aligned row actions.
- Fixes dropdown menu positioning and overflow behavior across compound controls.
- Eliminates idle CPU wakeups in the file stability coordinator for better battery life.
- Adds direct file manager opening and custom label editing to the Watched Folders settings tab.

## Notes Before Installing

- Windows and macOS builds are currently unsigned. Windows SmartScreen and macOS Gatekeeper may show a warning on first launch.
- Built-in updates are available for supported direct-download desktop builds. Store/package-manager installs will use their own update channels later.
- macOS 0.5.0 installations will not receive this version automatically. Install 0.5.1 manually from the DMG or PKG; future versions can then use the corrected update path.
- Microsoft Store, Snap, AUR, Homebrew, winget and Scoop packages are not published yet; use the downloads listed above for this release.
- Docker builds are provided as downloadable image archives for now.

## Verify Downloads

- [SHA256SUMS](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/SHA256SUMS)
- [Release manifest](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/release-manifest.json)
- [Build report](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.2/RELEASE_REPORT.md)

Support, bug reports and feature requests: cinerename@gmail.com
