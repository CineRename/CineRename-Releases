# CineRename Releases

This repository hosts CineRename public release artifacts while the application source repository remains private.

## Downloads

Installers are published from tagged builds of `CineRename/CineRename`:

- Windows x64: `.exe` and `.msi`
- macOS Apple Silicon: `.dmg` and `.pkg`
- macOS Intel: `.dmg` and `.pkg`
- Linux x64: `.AppImage`, `.deb` and `.rpm`
- NAS/server: Linux `x64` and `arm64` tarballs
- Docker: `ghcr.io/cinerename/cinerename`

Always verify downloaded files with the `SHA256SUMS.txt` asset from the same release.

## Docker

```bash
docker run --rm \
  -v /path/to/config:/config \
  -v /path/to/media:/media \
  ghcr.io/cinerename/cinerename:latest \
  auto /media/Inbox --to /media/Library --subs fr --json
```

## Support

CineRename is in beta. Release notes for each version list the exact supported installers and known limitations.
