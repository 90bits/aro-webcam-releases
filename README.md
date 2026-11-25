# Aro Webcam releases

Aro Webcam turns an Android phone into a webcam for a Windows PC, over USB or Wi-Fi.
This page holds Aro Desktop, the Windows app, and the source releases that go with it.

## Download

1. Open [Releases](https://github.com/90bits/aro-webcam-releases/releases) and pick the
   newest "Aro Desktop" release.
2. Download `AroWebcam-Setup-<version>-x64.exe` and run it.

Aro Desktop checks this page for updates.

## Requirements

Windows 10, version 1809 or later, or Windows 11. 64-bit.

## Check your download

Each release states the SHA-256 of its installer and carries a `.sha256` file. In
PowerShell:

    Get-FileHash .\AroWebcam-Setup-<version>-x64.exe -Algorithm SHA256

Compare the result with the value on the release.

## Help

- Help: https://arowebcam.com/help
- Support: https://arowebcam.com/support or support@arowebcam.com
- Discord: https://discord.gg/EAQYkKNtCT

## Terms and privacy

- Terms: https://arowebcam.com/terms
- Privacy: https://arowebcam.com/privacy

## Open source

Aro Desktop uses FFmpeg unmodified under the LGPL. The matching source is in the
release "FFmpeg 7.1.5 source pack for Aro Desktop" on this page. Aro Desktop includes
the notices for its third-party components.

Aro Webcam is made by [90bits](https://90bits.com).
