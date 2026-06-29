# CineRename Releases

Download CineRename directly from this page. The links below always point to the latest published version.

Current version: 0.5.0

## Recommended Downloads

Choose your operating system. These links are regenerated automatically by the release workflow whenever a new version is published.

### Windows

- [Installer .exe, recommended](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_x64-setup.exe) (8.3 MB)
- [Installer .msi](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_x64_en-US.msi) (11.5 MB)
- [Portable .zip](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_portable_windows_x64.zip) (11.1 MB)

### macOS

- [Apple Silicon .dmg](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_aarch64.dmg) (11.0 MB)
- [Intel .dmg](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_x64.dmg) (11.6 MB)
- [Apple Silicon .pkg](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_macos_arm64.pkg) (10.9 MB)
- [Intel .pkg](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_macos_x64.pkg) (11.5 MB)

macOS builds are currently unsigned. If macOS blocks the first launch, use **Open Anyway** from System Settings > Privacy & Security.

### Linux Desktop

- [AppImage x64, recommended](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_amd64.AppImage) (82.6 MB)
- [Debian / Ubuntu .deb](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_amd64.deb) (12.3 MB)
- [Fedora / openSUSE .rpm](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename-0.5.0-1.x86_64.rpm) (12.3 MB)
- [Portable POSIX archive](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_portable_posix_x64.tar.xz) (8.8 MB)

### NAS, Servers And Docker

- [Static NAS Linux x64 tarball](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_nas_linux_x86_64.tar.xz) (12.8 MB)
- [Static NAS Linux arm64 tarball](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_nas_linux_aarch64.tar.xz) (11.7 MB)
- [Docker image archive x64](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_docker_linux_amd64.tar.gz) (57.5 MB)
- [Docker image archive arm64](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_docker_linux_arm64.tar.gz) (56.0 MB)

Docker archives can be loaded with:

```bash
docker load -i CineRename_0.5.0_docker_linux_amd64.tar.gz
docker run --rm -v /path/to/config:/config -v /path/to/media:/media cinerename:0.5.0 auto /media/Inbox --to /media/Library --subs fr --json
```

## Verification

- [SHA256SUMS](https://github.com/CineRename/CineRename-Releases/releases/latest/download/SHA256SUMS)
- [Release notes](https://github.com/CineRename/CineRename-Releases/releases/latest/download/RELEASE_NOTES.md)
- [Release manifest](https://github.com/CineRename/CineRename-Releases/releases/latest/download/release-manifest.json)
- [Release report](https://github.com/CineRename/CineRename-Releases/releases/latest/download/RELEASE_REPORT.md)

## Auto-Update Metadata

Direct desktop builds use the `updater/` JSON files in this repository. Store and package-manager builds should use their own update channel.

- macOS x64: `updater/darwin/x86_64/latest.json`
- Linux x64: `updater/linux/x86_64/latest.json`
- Windows x64: `updater/windows/x86_64/latest.json`

## Notes

- Windows and macOS installers are unsigned for now.
- Version 0.5.0 is the first public release and the most stable CineRename build available today.
- The 0.5.x version number leaves room for final user feedback before the 1.0 milestone.
- Support, bug reports and feature requests: cinerename@gmail.com
