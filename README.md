# CineRename Releases

Téléchargez CineRename directement depuis cette page. Les liens ci-dessous pointent toujours vers la dernière version publiée.

Version actuelle : 0.5.0

## Téléchargements Recommandés

Choisissez simplement votre système. Les liens sont régénérés automatiquement par le workflow de release à chaque nouvelle version.

### Windows

- [Installateur .exe, recommandé](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_x64-setup.exe) (8.3 MB)
- [Installateur .msi](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_x64_en-US.msi) (11.5 MB)
- [Version portable .zip](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_portable_windows_x64.zip) (11.1 MB)

### macOS

- [Apple Silicon .dmg](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_aarch64.dmg) (11.0 MB)
- [Intel .dmg](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_x64.dmg) (11.6 MB)
- [Apple Silicon .pkg](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_macos_arm64.pkg) (10.9 MB)
- [Intel .pkg](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_macos_x64.pkg) (11.5 MB)

Les builds macOS ne sont pas encore signés. Si macOS bloque le premier lancement, utilisez **Ouvrir quand même** dans Réglages Système > Confidentialité et sécurité.

### Linux Desktop

- [AppImage x64, recommandé](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_amd64.AppImage) (82.6 MB)
- [Debian / Ubuntu .deb](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_amd64.deb) (12.3 MB)
- [Fedora / openSUSE .rpm](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename-0.5.0-1.x86_64.rpm) (12.3 MB)
- [Archive portable POSIX](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_portable_posix_x64.tar.xz) (8.8 MB)

### NAS, Serveurs Et Docker

- [Archive statique NAS Linux x64](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_nas_linux_x86_64.tar.xz) (12.8 MB)
- [Archive statique NAS Linux arm64](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_nas_linux_aarch64.tar.xz) (11.7 MB)
- [Archive image Docker x64](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_docker_linux_amd64.tar.gz) (57.5 MB)
- [Archive image Docker arm64](https://github.com/CineRename/CineRename-Releases/releases/latest/download/CineRename_0.5.0_docker_linux_arm64.tar.gz) (56.0 MB)

Les archives Docker peuvent être chargées avec :

```bash
docker load -i CineRename_0.5.0_docker_linux_amd64.tar.gz
docker run --rm -v /path/to/config:/config -v /path/to/media:/media cinerename:0.5.0 auto /media/Inbox --to /media/Library --subs fr --json
```

## Vérification

- [SHA256SUMS](https://github.com/CineRename/CineRename-Releases/releases/latest/download/SHA256SUMS)
- [Manifest de release](https://github.com/CineRename/CineRename-Releases/releases/latest/download/release-manifest.json)
- [Rapport de release](https://github.com/CineRename/CineRename-Releases/releases/latest/download/RELEASE_REPORT.md)

## Métadonnées De Mise À Jour

Les builds desktop directs utilisent les fichiers JSON `updater/` de ce dépôt. Les stores et gestionnaires de paquets doivent utiliser leur propre canal de mise à jour.

- Linux x64: `updater/linux/x86_64/latest.json`
- Windows x64: `updater/windows/x86_64/latest.json`
- macOS x64: `updater/darwin/x86_64/latest.json`

## Notes

- Les installateurs Windows et macOS ne sont pas encore signés.
- La série `0.5.x` est le canal public pre-1.0.
- Support, bugs et demandes de fonctionnalités : cinerename@gmail.com
