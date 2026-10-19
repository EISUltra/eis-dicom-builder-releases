# EIS DICOM Builder — downloads

Installers for **EIS DICOM Builder**, the clinic app that turns X-ray and photo exports into DICOM and sends them to PACS. No sign-in is needed to download. These links always give the newest version:

| Computer | Download |
|---|---|
| **Windows 10 / 11** | [EIS-DICOM-Builder-win-x64.exe](https://github.com/EISUltra/eis-dicom-builder-releases/releases/latest/download/EIS-DICOM-Builder-win-x64.exe) |
| **Mac with Apple M1 or newer** | [EIS-DICOM-Builder-mac-arm64.dmg](https://github.com/EISUltra/eis-dicom-builder-releases/releases/latest/download/EIS-DICOM-Builder-mac-arm64.dmg) |
| **Mac with an Intel processor** | [EIS-DICOM-Builder-mac-x64.dmg](https://github.com/EISUltra/eis-dicom-builder-releases/releases/latest/download/EIS-DICOM-Builder-mac-x64.dmg) |

Not sure which Mac you have? Apple menu → **About This Mac** → look at **Chip**.

All versions and release notes: [Releases](https://github.com/EISUltra/eis-dicom-builder-releases/releases)

## Installing

**Windows:** run the downloaded `.exe`. It installs for the current user and adds Desktop and Start-menu shortcuts. If Windows shows "Windows protected your PC", click **More info → Run anyway**.

**Mac:** open the `.dmg` and drag **EIS DICOM Builder** onto **Applications**. On first launch, if macOS blocks it, open **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.

**Upgrading:** install over the existing version. Patients, studies, images, settings and PACS destinations are kept. From version 1.2 on, Windows installs update themselves from this page; Mac installs will too once the app is code-signed.

## About this repository

This repository holds installers only. The source code is private. Installed apps read the update information published here, so please don't delete releases.
