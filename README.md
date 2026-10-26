# CineRename Releases

Download CineRename directly from this page. The links below always point to the latest published version.

Current version: 0.5.9

## Recommended Downloads

Choose your operating system. These links are regenerated automatically by the release workflow whenever a new version is published.

### Windows

- [Installer .exe, recommended](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_x64-setup.exe) (8.9 MB)
- [Installer .msi](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_x64_en-US.msi) (12.2 MB)
- [Portable .zip](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_portable_windows_x64.zip) (11.9 MB)

### macOS

- [Apple Silicon .dmg](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_aarch64.dmg) (13.3 MB)
- [Intel .dmg](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_x64.dmg) (14.2 MB)
- [Apple Silicon .pkg](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_macos_arm64.pkg) (11.4 MB)
- [Intel .pkg](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_macos_x64.pkg) (12.5 MB)

macOS builds are currently unsigned. If macOS blocks the first launch, use **Open Anyway** from System Settings > Privacy & Security.

### Linux Desktop

- [AppImage x64, recommended](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_amd64.AppImage) (84.3 MB)
- [Debian / Ubuntu .deb](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_amd64.deb) (12.8 MB)
- [Fedora / openSUSE .rpm](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename-0.5.9-1.x86_64.rpm) (12.8 MB)
- [Portable POSIX archive](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_portable_posix_x64.tar.xz) (9.2 MB)

### NAS, Servers And Docker

- [Static NAS Linux x64 tarball](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_nas_linux_x86_64.tar.xz) (13.8 MB)
- [Static NAS Linux arm64 tarball](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_nas_linux_aarch64.tar.xz) (12.5 MB)
- [Docker image archive x64](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_docker_linux_amd64.tar.gz) (68.4 MB)
- [Docker image archive arm64](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.9_docker_linux_arm64.tar.gz) (65.9 MB)

Docker archives can be loaded with:

```bash
docker load -i CineRename_0.5.9_docker_linux_amd64.tar.gz
docker run --rm -v /path/to/config:/config -v /path/to/media:/media cinerename:0.5.9 auto /media/Inbox --to /media/Library --subs fr --json
```

## Documentation

- [Documentation](https://cinerename.app/docs/)
- [Installation](https://cinerename.app/docs/installation)
- [Getting started](https://cinerename.app/docs/getting-started)
- [CLI and headless usage](https://cinerename.app/docs/cli)
- [Troubleshooting](https://cinerename.app/docs/troubleshooting)

## Verification

- [SHA256SUMS](https://github.com/CineRename/CineRename-Releases/releases/latest/download/SHA256SUMS)
- [Release notes](https://github.com/CineRename/CineRename-Releases/releases/latest/download/RELEASE_NOTES.md)
- [Localized release notes data](https://github.com/CineRename/CineRename-Releases/releases/latest/download/RELEASE_NOTES.locales.json)
- [Release manifest](https://github.com/CineRename/CineRename-Releases/releases/latest/download/release-manifest.json)
- [Release report](https://github.com/CineRename/CineRename-Releases/releases/latest/download/RELEASE_REPORT.md)

## Auto-Update Metadata

Direct desktop builds use the `updater/` JSON files in this repository. Store and package-manager builds should use their own update channel.

- macOS arm64 current-version path: `updater/darwin/aarch64/0.5.9.json`
- macOS arm64 legacy path, frozen on 0.5.0: `updater/darwin/aarch64/latest.json`
- macOS x64 current-version path: `updater/darwin/x86_64/0.5.9.json`
- macOS x64 legacy path, frozen on 0.5.0: `updater/darwin/x86_64/latest.json`
- Linux x64 current-version path: `updater/linux/x86_64/0.5.9.json`
- Linux x64 legacy path: `updater/linux/x86_64/latest.json`
- Windows x64 current-version path: `updater/windows/x86_64/0.5.9.json`
- Windows x64 legacy path: `updater/windows/x86_64/latest.json`

## Notes

- Windows and macOS installers are unsigned for now.
- macOS installations still on 0.5.0 must install 0.5.9 manually from a .dmg or .pkg because their legacy updater remains frozen on 0.5.0.
- Version 0.5.9 is the current stable CineRename release.
- Support, bug reports and feature requests: cinerename@gmail.com
