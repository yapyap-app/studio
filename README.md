# yapyap — releases

Public distribution channel for **yapyap** desktop binaries and the
auto-update manifest (`latest.json`).

> **This repository contains no source code.** yapyap is a closed-source,
> commercial product. Downloading or using these binaries is governed by the
> End User License Agreement in [`LICENSE`](./LICENSE).

- **Product:** https://yap-yap.app
- **Downloads:** the [Releases](https://github.com/yapyap-app/releases/releases) tab
- **Source:** private

## What's here

Each release ships code-signed / notarised installers for macOS (Apple
Silicon), Windows, and Linux, alongside a [minisign](https://jedisct1.github.io/minisign/)-signed
`latest.json` consumed by yapyap's in-app auto-updater. Updates are verified
against a public key embedded in the app before they are installed — a binary
hosted here cannot be tampered with undetected.

This repo exists only so the auto-updater (and your downloads) can reach the
binaries over a public URL while the application source stays private.

---

© 2026 yapyap. All rights reserved.
