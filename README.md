# Attention Player — builds

Distribution channel for sideloaded [Attention Player](https://github.com/yousef-awad/FlutterFaceRec)
builds. No source lives here.

The `latest` release holds two assets, replaced on every publish:

- `update.json` — the manifest installed apps poll on launch
- `attention-player-<versionCode>.apk` — the build it points at

Installed instances read `update.json` at startup and offer the newer build.
This repo is public because devices fetch both files without credentials.

Published by `scripts/release.ps1` in the source repo.
