# WAYLOAM Releases

Public binary distribution for the private [`loam-tools/wayloam`](https://github.com/loam-tools/wayloam) Android source repository.

This repository contains only release artifacts and update metadata. Application source remains private.

## Contents

- GitHub prereleases containing signed WAYLOAM alpha APKs
- `latest.json` used by the in-app updater
- `manifests/` containing versioned update metadata
- SHA-256 sidecars for published APKs

## Update feed

The Android app reads:

```text
https://raw.githubusercontent.com/loam-tools/wayloam-releases/main/latest.json
```

`latest.json` points to the currently published signed APK and includes its version code, file size, SHA-256 digest and release notes.

## Ownership

WAYLOAM is maintained under **Loam Tools**.

Do not place signing keys, repository tokens or private source code in this repository.
