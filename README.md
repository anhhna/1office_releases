# 1office desktop releases

Installers for the **1office** desktop app. It opens **https://office.infinyt.app** on first
start (create an account there or sign in). Companies with their own 1office server can
change the address in the app.

**[⬇ Download the latest release](https://github.com/anhhna/1office_releases/releases/latest)**

| Platform | File |
|---|---|
| Windows 10/11 (64-bit) | `1office-<version>-win-x64.exe` |
| macOS, Apple silicon (M1–M4) | `1office-<version>-mac-arm64.dmg` |
| macOS, Intel | `1office-<version>-mac-x64.dmg` |
| Linux (any distro) | `1office-<version>-linux-x86_64.AppImage` |
| Ubuntu / Debian | `1office-<version>-linux-amd64.deb` |

## Installing

- **Windows:** run the installer. If SmartScreen shows "Windows protected your PC", choose *More info → Run anyway* (Windows builds are not code-signed yet).
- **macOS:** open the .dmg and drag 1office to Applications. The app is signed and notarized by Apple, so it opens normally.
- **Linux:** `chmod +x 1office-*.AppImage && ./1office-*.AppImage`, or `sudo apt install ./1office-*-linux-amd64.deb`.

## Updates

From version 1.1.0 the app updates itself: it checks this page in the background, downloads
new versions and asks you to restart. *Check for Updates…* is in the 1office menu (macOS) or the
Help menu (Windows/Linux). Version 1.0.0 has no updater; install 1.1.0 manually once.

The `latest*.yml` and `.blockmap` files in each release are read by the updater. Verify downloads
with `SHA256SUMS.txt`.

## About

Document editing is powered by ONLYOFFICE Docs (GNU AGPL v3). ONLYOFFICE is a
trademark of Ascensio System SIA; 1office is not affiliated with Ascensio System SIA.
This repository only hosts binaries.
