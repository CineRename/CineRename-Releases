# CineRename 0.5.5

CineRename 0.5.5 is the current stable release for movie, TV and anime library cleanup, bulk renaming and NAS/server use.

## Download

Recommended installers:

- [Windows x64 installer (.exe)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/CineRename_0.5.5_x64-setup.exe) (8.7 MB)
- [Windows x64 installer (.msi)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/CineRename_0.5.5_x64_en-US.msi) (12.0 MB)
- [macOS Apple Silicon (.dmg)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/CineRename_0.5.5_aarch64.dmg) (12.4 MB)
- [macOS Intel (.dmg)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/CineRename_0.5.5_x64.dmg) (13.2 MB)
- [Linux x64 AppImage](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/CineRename_0.5.5_amd64.AppImage) (84.0 MB)
- [Linux x64 .deb](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/CineRename_0.5.5_amd64.deb) (12.6 MB)
- [Linux x64 .rpm](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/CineRename-0.5.5-1.x86_64.rpm) (12.6 MB)

Server and NAS builds:

- [NAS / server Linux x64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/CineRename_0.5.5_nas_linux_x86_64.tar.xz) (13.6 MB)
- [NAS / server Linux arm64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/CineRename_0.5.5_nas_linux_aarch64.tar.xz) (12.3 MB)
- [Docker archive x64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/CineRename_0.5.5_docker_linux_amd64.tar.gz) (68.2 MB)
- [Docker archive arm64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/CineRename_0.5.5_docker_linux_arm64.tar.gz) (65.6 MB)

You can also open the [release page](https://github.com/CineRename/CineRename-Releases/releases/tag/v0.5.5) for the complete asset list.
Full installation and usage docs are available at [cinerename.app/docs](https://cinerename.app/docs/).

## Highlights

- **macOS NAS / SMB compatibility**: adds a fallback when a network volume does not support exclusive renaming, covering staging, finalization, rollback and undo.
- **Copies to network volumes**: copying can continue when the destination explicitly does not support preserving POSIX permissions; real access and I/O errors still stop the operation.
- **Naming templates**: handles spaces inside tokens such as `{ title }` and preserves token-like text contained in media titles.
- **Media details**: corrects video bit-depth detection for formats such as NV12 and for files reporting an unknown raw bit depth.
- **Subtitle timing**: fixes an overflow when applying drift correction with large offsets and improves precision over long durations.
- **Archive cache**: prevents cleanup crashes caused by out-of-range timestamps in cache markers.
- **Security**: updates TLS and frontend dependencies and prevents hooks and Plex/Jellyfin refresh requests from automatically forwarding authentication data through redirects. Configure the final endpoint URL directly.
- **Performance**: reduces allocations during natural path sorting and template rendering.
- **Usage analytics**: restores website-to-app attribution and adds screen and settings navigation events.

## Notes Before Installing

- Windows and macOS builds are currently unsigned. Windows SmartScreen and macOS Gatekeeper may show a warning on first launch.
- Built-in updates are available for supported direct-download desktop builds. Store/package-manager editions use their own update channels.
- macOS 0.5.0 installations will not receive this version automatically. Install this release manually from the DMG or PKG; future versions can then use the corrected update path.
- Microsoft Store, Snap and other package-manager editions use separate publication channels; their availability and update timing may differ from this release.
- Docker builds are provided as downloadable image archives for now.

## Verify Downloads

- [SHA256SUMS](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/SHA256SUMS)
- [Release manifest](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/release-manifest.json)
- [Build report](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.5/RELEASE_REPORT.md)

Support, bug reports and feature requests: cinerename@gmail.com
