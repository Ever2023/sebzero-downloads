# SebZero — The Frozen Realm

Official Windows launcher and signed client downloads.

**[Download SebZero-Launcher.jar](https://github.com/Ever2023/sebzero-downloads/releases/latest/download/SebZero-Launcher.jar)**

1. Install **64-bit Java 8** if you do not already have it.
2. Open **SebZero-Launcher.jar**.
3. Let the launcher install the client, then choose **Play SebZero**.

The obfuscated JAR contains the icy launcher, updater settings and public
verification key. No ZIP extraction, scripts, sidecar files or administrator
access is needed. Java is installed separately.

Your launcher checks for signed client updates automatically. Keep using the
launcher when new updates are announced. The game cache and preferences remain
between client versions. The online count refreshes every 30 seconds when the
world supports the status query; an unavailable count does not prevent playing.

If an update cannot be downloaded temporarily, the launcher can offer your last
verified installed client. A compatible world must still be online.

Client startup problems are recorded in
`%LOCALAPPDATA%\SebZero\launcher\logs\client-latest.log`.

[Release history](https://github.com/Ever2023/sebzero-downloads/releases)

This repository contains player downloads. It does not contain game-server
source code, account saves or private keys. Use the latest launcher download
above. Release 1.0.3 adds the single-JAR launcher. Both launcher and client remain
obfuscated, and existing game caches and player progress remain.
