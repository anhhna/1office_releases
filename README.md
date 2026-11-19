# 1office desktop releases

Installers for the **1office** desktop app. The app connects to your company's
1office server; ask your IT team for the server address.

**[⬇ Download the latest release](https://github.com/anhhna/1office_releases/releases/latest)**

| Platform | File |
|---|---|
| Windows 10/11 (64-bit) | `1office-<version>-win-x64.exe` |
| macOS, Apple silicon (M1–M4) | `1office-<version>-mac-arm64.dmg` |
| macOS, Intel | `1office-<version>-mac-x64.dmg` |
| Linux (any distro) | `1office-<version>-linux-x86_64.AppImage` |
| Ubuntu / Debian | `1office-<version>-linux-amd64.deb` |

## Installing

- **Windows:** run the installer. If SmartScreen shows "Windows protected your PC", choose *More info → Run anyway* (builds are not code-signed yet).
- **macOS:** open the .dmg and drag 1office to Applications. The first time, right-click the app → *Open*. If macOS says the app "is damaged", run `xattr -cr /Applications/1office.app` (builds are not notarized yet).
- **Linux:** `chmod +x 1office-*.AppImage && ./1office-*.AppImage`, or `sudo apt install ./1office-*-linux-amd64.deb`.

## About

Document editing is powered by ONLYOFFICE Docs (GNU AGPL v3). ONLYOFFICE is a
trademark of Ascensio System SIA; 1office is not affiliated with Ascensio System SIA.
This repository only hosts binaries.
