# ACE LC ESP32 OTA releases

Public, machine-readable OTA artifacts for ACE LC ESP32 devices. Source code is
kept in a separate private repository.

- `version.json` is the manifest URL sent to devices by command `0x24`.
- Firmware binaries are attached to matching GitHub Releases.
- The firmware accepts manifests and binaries only from this repository.
- Each manifest pins the exact version, byte size, and SHA-256 digest.

Current manifest URL:

`https://github.com/778912890-maker/ACE_LC_ESP32_OTA_Releases/releases/latest/download/version.json`
