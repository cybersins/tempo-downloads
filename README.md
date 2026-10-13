# Tempo downloads

Make every move count. Tempo is a free, native Apple Silicon Mac companion for Garmin watches.

This repository contains public installers, installation instructions and release notes. Application source is not published here. GitHub's automatically generated source archives contain only this repository's public documentation.

## Download Tempo v0.1.0

- [Download for Mac (DMG)](https://github.com/cybersins/tempo-downloads/releases/download/v0.1.0/Tempo-0.1.0-arm64.dmg)
- [ZIP alternative](https://github.com/cybersins/tempo-downloads/releases/download/v0.1.0/Tempo-0.1.0-arm64.zip)
- [SHA-256 checksums](https://github.com/cybersins/tempo-downloads/releases/download/v0.1.0/Tempo-0.1.0-arm64.sha256)
- [Latest release and notes](https://github.com/cybersins/tempo-downloads/releases/latest)

Requires **Apple Silicon (M-series) and macOS 26 or later**. Installers are Developer ID signed and notarized by Apple. Tickets are attached to the app and DMG; the ZIP contains the same stapled app.

## Install

1. Quit any running copy of Tempo.
2. Open the DMG and drag Tempo.app into Applications. Alternatively, extract the ZIP and move the app into Applications.
3. Eject the disk image and open Tempo from Applications.
4. Connect your Garmin watch with a USB data cable, close Garmin Express and its background service, then choose Quick sync.

No account or Homebrew installation is required. Updating the app preserves the local library and settings. Ordinary sync does not delete watch data. Cleanup requires explicit approval and checked recovery copies.

Forerunner 970 has been tested; other models remain unverified. See release notes for supported features and known limitations. Native Connect IQ Store integration, firmware updates and licensed map activation are not supported.

## Integrity

Download the checksum file and both installers into the same folder, then run:

```sh
shasum -a 256 -c Tempo-0.1.0-arm64.sha256
```

## Feedback and support

Developed independently by Rishi Narang. Tempo is not funded, developed or endorsed by Garmin.

Feedback: **hello@vibemode.io**. Optional support: [Buy Me a Coffee](https://buymeacoffee.com/ideally.us).
