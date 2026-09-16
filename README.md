# Forged Idle — Releases

Windows builds of **Forged Idle**, an idle RPG.

## Download

Grab the latest `Forged-Idle_*_x64-setup.exe` from
[Releases](https://github.com/Freywood/forge-idle-releases/releases/latest).

The installer is not code-signed, so Windows SmartScreen will warn on first run —
**More info → Run anyway**.

## Updating

The game updates itself. It checks on launch, tells you what changed, and waits for you
to say yes. **Your characters and progress are kept**: saves live in
`%APPDATA%\net.sidia.forgedidle\` and the installer only replaces the program folder.

## What's in a release

| File | For |
| ---- | --- |
| `Forged-Idle_*_x64-setup.exe` | a fresh install |
| `Forged-Idle_*_x64-setup.nsis.zip` + `.sig` | the in-game updater |
| `latest.json` | the manifest the updater polls |

This repository holds **binaries only** — no source. Bundles are signed with a minisign
key and the game refuses anything that does not verify.
