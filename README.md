# PocketRocket releases

Release APKs of **PocketRocket**: Claude Code on an Android phone, in one app. Your phone becomes the machine. Repos, sessions and tools all live on it, and Claude runs there, not in the cloud.

> **A personal tool, still under development.** I built PocketRocket for myself, for my own phone and my own way of working. It is not a product, there is no support, and things change or break without notice.

This repo holds only the release builds. The app checks the [Releases](../../releases) here when you tap Update in Settings → PocketRocket.

## Install

1. Download `pocketrocket-vX.Y.Z-arm64.apk` from the latest release. It runs on arm64 phones with Android 7 or newer, and is tested on Android 16.
2. Install it, allowing installs from your browser when Android asks.
3. On first run it downloads and sets up Claude Code, git, gh, node and npm. This takes a few minutes. Claude Code comes straight from Anthropic and is checked against their manifest; it is never bundled.

PocketRocket uses the package id `com.termux`, so it can't be installed next to the Termux app.

## Notes

- Each release lists its SHA-256. The in-app updater refuses any file whose checksum doesn't match.
- PocketRocket is a fork of [Termux](https://github.com/termux/termux-app) (GPLv3). Claude Code is Anthropic's software, used under their terms. PocketRocket is not affiliated with Anthropic or the Termux project.
