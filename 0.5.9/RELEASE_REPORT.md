# CineRename 0.5.9 Release Report

Generated at: 2026-10-26T10:03:34.846Z
Commit: 5913d76de6318e935a5a1daf782924869a6937e1
GitHub Actions run: https://github.com/CineRename/CineRename/actions/runs/40300581927

## Generated Artifacts

- `CineRename_0.5.9_aarch64.dmg`
- `CineRename_0.5.9_amd64.AppImage`
- `CineRename_0.5.9_amd64.AppImage.sig`
- `CineRename_0.5.9_amd64.deb`
- `CineRename_0.5.9_amd64.deb.sig`
- `cinerename_0.5.9_amd64.snap`
- `CineRename_0.5.9_docker_linux_amd64.tar.gz`
- `CineRename_0.5.9_docker_linux_arm64.tar.gz`
- `CineRename_0.5.9_macos_arm64.app.tar.gz`
- `CineRename_0.5.9_macos_arm64.app.tar.gz.sig`
- `CineRename_0.5.9_macos_arm64.pkg`
- `CineRename_0.5.9_macos_x64.app.tar.gz`
- `CineRename_0.5.9_macos_x64.app.tar.gz.sig`
- `CineRename_0.5.9_macos_x64.pkg`
- `CineRename_0.5.9_nas_linux_aarch64.tar.xz`
- `CineRename_0.5.9_nas_linux_x86_64.tar.xz`
- `CineRename_0.5.9_portable_posix_x64.tar.xz`
- `CineRename_0.5.9_portable_windows_x64.zip`
- `CineRename_0.5.9_x64_en-US.msi`
- `CineRename_0.5.9_x64_en-US.msi.sig`
- `CineRename_0.5.9_x64-setup.exe`
- `CineRename_0.5.9_x64-setup.exe.sig`
- `CineRename_0.5.9_x64.dmg`
- `CineRename_0.5.9_x64.msix`
- `CineRename-0.5.9-1.x86_64.rpm`
- `CineRename-0.5.9-1.x86_64.rpm.sig`

## Not Generated In This Run


## Notes

- Windows and macOS artifacts are intentionally OS-unsigned, so SmartScreen or Gatekeeper warnings are expected. Tauri updater archives are signed separately.
- Microsoft Store and Snap Store submissions run in separate jobs of this workflow when requested; this report does not confirm Store approval or availability.
- macOS 0.5.0 clients are intentionally not offered 0.5.9 through latest.json; corrected-client versioned paths advance to this release, while OS-unsigned .dmg/.pkg installers remain available for the required manual transition.
- Official Lemon Squeezy production variant IDs are embedded; release-time environment variables can override them if the store changes.
- qBittorrent, Transmission and JDownloader production tests require reachable services.
