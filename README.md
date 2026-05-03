qBittorrent Enhanced Edition Alpha
------------------------------------------

This repository contains an alpha fork of qBittorrent with Enhanced Edition behavior and packaging updates.

### What this repo is
- A maintained fork based on upstream qBittorrent (C++/Qt + libtorrent)
- An alpha release channel for testing Enhanced Edition builds
- A source tree that produces branded Enhanced Edition installers/artifacts

### Key differences from upstream
- Application/window branding uses **qBittorrent Enhanced Edition**
- Enhanced peer-filter and anti-leech options are exposed in UI/WebUI
- Windows installer/uninstaller branding and shortcut names are fork-specific
- Linux AppImage workflow is modernized for current build environments

### Release artifacts
Releases in this fork are published as alpha tags and include:
- Windows installer (`qbittorrent_enhanced_edition_*_setup.exe`)
- Linux AppImage (`qBittorrent-Enhanced-Edition-x86_64.AppImage`)

### Versioning
Fork releases use an upstream-based version plus fork suffix, for example:
- `release-5.3.0-ee.1-alpha`

### Build and install
- Build instructions: [INSTALL](INSTALL)

### Upstream and credits
- Upstream repository: https://github.com/qbittorrent/qBittorrent
- Enhanced Edition reference project: https://github.com/c0re100/qBittorrent-Enhanced-Edition

This fork is based on qBittorrent. For upstream documentation and project details, see:
- https://www.qbittorrent.org
- https://wiki.qbittorrent.org
