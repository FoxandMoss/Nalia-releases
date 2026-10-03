# Nalia Releases

Public Windows installer and release assets for **Nalia**, the Natural Adaptive Language Interface Assistant.

The application source lives in the private `FoxandMoss/Nalia` repository. This repository intentionally contains public release artifacts only.

## Permanent Windows download

Use GitHub Releases, not a raw repository-file URL.

Website and other public download buttons should use this versionless path:

`https://github.com/FoxandMoss/Nalia-releases/releases/latest/download/Nalia-Windows-Installer.exe`

Each public release publishes the current Windows installer under the stable asset name `Nalia-Windows-Installer.exe` and verifies the downloaded asset checksum against the staged build.

A bootstrap installer may also be attached to releases for recovery/update use, but the public website download must not depend on a `/raw/main/windows/...` repository file.

Nalia is currently early Windows development. Do not treat a release as verified until its release workflow and runtime checks complete successfully.
