# CineRename 0.5.11

CineRename 0.5.11 is the current stable release for movie, TV and anime library cleanup, bulk renaming and NAS/server use.

## Download

Recommended installers:

- [Windows x64 installer (.exe)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/CineRename_0.5.11_x64-setup.exe) (9.0 MB)
- [Windows x64 installer (.msi)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/CineRename_0.5.11_x64_en-US.msi) (12.4 MB)
- [macOS Apple Silicon (.dmg)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/CineRename_0.5.11_aarch64.dmg) (13.3 MB)
- [macOS Intel (.dmg)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/CineRename_0.5.11_x64.dmg) (14.2 MB)
- [Linux x64 AppImage](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/CineRename_0.5.11_amd64.AppImage) (84.4 MB)
- [Linux x64 .deb](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/CineRename_0.5.11_amd64.deb) (13.0 MB)
- [Linux x64 .rpm](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/CineRename-0.5.11-1.x86_64.rpm) (13.0 MB)

Server and NAS builds:

- [NAS / server Linux x64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/CineRename_0.5.11_nas_linux_x86_64.tar.xz) (13.9 MB)
- [NAS / server Linux arm64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/CineRename_0.5.11_nas_linux_aarch64.tar.xz) (12.6 MB)
- [Docker archive x64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/CineRename_0.5.11_docker_linux_amd64.tar.gz) (68.6 MB)
- [Docker archive arm64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/CineRename_0.5.11_docker_linux_arm64.tar.gz) (66.1 MB)

You can also open the [release page](https://github.com/CineRename/CineRename-Releases/releases/tag/v0.5.11) for the complete asset list.
Full installation and usage docs are available at [cinerename.app/docs](https://cinerename.app/docs/).

## Highlights

- Fixes launch crashes on macOS Apple Silicon (M-series chips) caused by hardened runtime conflicts with ad-hoc signing.
- Eliminates repeated macOS Keychain authorization prompts on application startup and credential access.
- Restores instant native clipboard copying for diagnostics, logs, and configuration exports in the Support screen.

## Notes Before Installing

- Windows installers are unsigned. macOS apps use a free ad-hoc signature without Apple notarization. SmartScreen or Gatekeeper may still require approval on first launch.
- Built-in updates are available for supported direct-download desktop builds. Store/package-manager editions use their own update channels.
- macOS 0.5.0 installations will not receive this version automatically. Install this release manually from the DMG or PKG; future versions can then use the corrected update path.
- Microsoft Store, Snap and other package-manager editions use separate publication channels; their availability and update timing may differ from this release.
- Docker builds are provided as downloadable image archives for now.

## Verify Downloads

- [SHA256SUMS](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/SHA256SUMS)
- [Release manifest](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/release-manifest.json)
- [Build report](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.11/RELEASE_REPORT.md)

Support, bug reports and feature requests: cinerename@gmail.com
