# CineRename 0.5.4

CineRename 0.5.4 is the current stable release for movie, TV and anime library cleanup, bulk renaming and NAS/server use.

## Download

Recommended installers:

- [Windows x64 installer (.exe)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/CineRename_0.5.4_x64-setup.exe) (8.6 MB)
- [Windows x64 installer (.msi)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/CineRename_0.5.4_x64_en-US.msi) (11.9 MB)
- [macOS Apple Silicon (.dmg)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/CineRename_0.5.4_aarch64.dmg) (12.3 MB)
- [macOS Intel (.dmg)](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/CineRename_0.5.4_x64.dmg) (13.1 MB)
- [Linux x64 AppImage](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/CineRename_0.5.4_amd64.AppImage) (83.3 MB)
- [Linux x64 .deb](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/CineRename_0.5.4_amd64.deb) (12.5 MB)
- [Linux x64 .rpm](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/CineRename-0.5.4-1.x86_64.rpm) (12.5 MB)

Server and NAS builds:

- [NAS / server Linux x64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/CineRename_0.5.4_nas_linux_x86_64.tar.xz) (13.6 MB)
- [NAS / server Linux arm64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/CineRename_0.5.4_nas_linux_aarch64.tar.xz) (12.3 MB)
- [Docker archive x64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/CineRename_0.5.4_docker_linux_amd64.tar.gz) (68.2 MB)
- [Docker archive arm64](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/CineRename_0.5.4_docker_linux_arm64.tar.gz) (65.6 MB)

You can also open the [release page](https://github.com/CineRename/CineRename-Releases/releases/tag/v0.5.4) for the complete asset list.
Full installation and usage docs are available at [cinerename.app/docs](https://cinerename.app/docs/).

## Highlights

- Full app localization in Spanish (`Español`) and Simplified Chinese (`简体中文`), covering all 24 UI modules (preview, templates, providers, watched folders, subtitles, checksums, history, settings, dialogs, and errors).
- Fixes Linux Landlock sandbox incompatibility (`ENOSYS`) on Synology NAS (DSM) and older kernels: automatic graceful degradation when Landlock LSM is unsupported, preventing Docker crash loops and ensuring WebUI server startup on port 8787. Added `--no-sandbox` (`--no-landlock`) flags and `CINERENAME_DISABLE_LANDLOCK=1` environment variable.
- Resolves false positive "file no longer available on disk" warnings on Windows UNC network shares by properly normalizing extended verbatim paths (`\\?\UNC\...` reconstructed cleanly to `\\server\share\...`), fixing imports, dry-run CSV exports, and history undo.
- Major filesystem hardening: native Windows long path support (> 260 chars) across Win32 APIs and `<longPathAware>` manifest, strict safe limits on temporary filename lengths (< 255 bytes), transparent support for cloud-synced files (OneDrive, Dropbox) and NTFS junctions, robust fallback for Linux CIFS/SMB/NFS renames, and best-effort access time preservation for NAS copies.
- Automatic detection of the operating system's native language on startup, seamlessly adapting the interface to English, French, Spanish, or Simplified Chinese.
- Integrated Spanish and Chinese subtitle search support with providers OpenSubtitles and SubDL.
- Strict automated translation verification tests ensuring 100% key parity, consistent parameter interpolation, and typography compliance across all supported languages.

## Notes Before Installing

- Windows and macOS builds are currently unsigned. Windows SmartScreen and macOS Gatekeeper may show a warning on first launch.
- Built-in updates are available for supported direct-download desktop builds. Store/package-manager installs will use their own update channels later.
- macOS 0.5.0 installations will not receive this version automatically. Install 0.5.1 manually from the DMG or PKG; future versions can then use the corrected update path.
- Microsoft Store, Snap, AUR, Homebrew, winget and Scoop packages are not published yet; use the downloads listed above for this release.
- Docker builds are provided as downloadable image archives for now.

## Verify Downloads

- [SHA256SUMS](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/SHA256SUMS)
- [Release manifest](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/release-manifest.json)
- [Build report](https://github.com/CineRename/CineRename-Releases/releases/download/v0.5.4/RELEASE_REPORT.md)

Support, bug reports and feature requests: cinerename@gmail.com
