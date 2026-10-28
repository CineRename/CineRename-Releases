# CineRename 0.5.13 Release Report

Generated at: 2026-10-28T21:55:32.456Z
Commit: bbdf2934caa7c6be4fa380f204183557b9e00c96
GitHub Actions run: https://github.com/CineRename/CineRename/actions/runs/40772515974

## Generated Artifacts

- `CineRename_0.5.13_aarch64.dmg`
- `CineRename_0.5.13_amd64.AppImage`
- `CineRename_0.5.13_amd64.AppImage.sig`
- `CineRename_0.5.13_amd64.deb`
- `CineRename_0.5.13_amd64.deb.sig`
- `cinerename_0.5.13_amd64.snap`
- `CineRename_0.5.13_docker_linux_amd64.tar.gz`
- `CineRename_0.5.13_docker_linux_arm64.tar.gz`
- `CineRename_0.5.13_macos_arm64.app.tar.gz`
- `CineRename_0.5.13_macos_arm64.app.tar.gz.sig`
- `CineRename_0.5.13_macos_arm64.pkg`
- `CineRename_0.5.13_macos_x64.app.tar.gz`
- `CineRename_0.5.13_macos_x64.app.tar.gz.sig`
- `CineRename_0.5.13_macos_x64.pkg`
- `CineRename_0.5.13_nas_linux_aarch64.tar.xz`
- `CineRename_0.5.13_nas_linux_x86_64.tar.xz`
- `CineRename_0.5.13_portable_posix_x64.tar.xz`
- `CineRename_0.5.13_portable_windows_x64.zip`
- `CineRename_0.5.13_x64_en-US.msi`
- `CineRename_0.5.13_x64_en-US.msi.sig`
- `CineRename_0.5.13_x64-setup.exe`
- `CineRename_0.5.13_x64-setup.exe.sig`
- `CineRename_0.5.13_x64.dmg`
- `CineRename_0.5.13_x64.msix`
- `CineRename-0.5.13-1.x86_64.rpm`
- `CineRename-0.5.13-1.x86_64.rpm.sig`

## Not Generated In This Run


## Notes

- Windows and macOS artifacts are intentionally OS-unsigned, so SmartScreen or Gatekeeper warnings are expected. Tauri updater archives are signed separately.
- Microsoft Store and Snap Store submissions run in separate jobs of this workflow when requested; this report does not confirm Store approval or availability.
- macOS 0.5.0 clients are intentionally not offered 0.5.13 through latest.json; corrected-client versioned paths advance to this release, while OS-unsigned .dmg/.pkg installers remain available for the required manual transition.
- Official Lemon Squeezy production variant IDs are embedded; release-time environment variables can override them if the store changes.
- qBittorrent, Transmission and JDownloader production tests require reachable services.
