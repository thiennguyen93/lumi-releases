# Lumi Releases

Downloads for **Lumi** — global shortcuts, text snippets and a Caps Lock Hyper
key, from the macOS menu bar.

## Install

1. Download the latest **`.dmg`** from
   [Releases](https://github.com/thiennguyen93/lumi-releases/releases/latest).
2. Open it and drag **Lumi** into **Applications**.
3. Launch it. Lumi appears in the menu bar, not the Dock.

One universal build covers both Apple Silicon and Intel Macs. Lumi needs
Accessibility permission to send keystrokes and remap Caps Lock; it asks on
first launch.

## Updates

Lumi updates itself. Choose **Check for Updates…** from the menu bar icon, or
open **About** in Settings. To update by hand, download the newest `.dmg` and
replace the app.

## What's in a release

| Asset | What it's for |
| --- | --- |
| `Lumi_<version>_universal.dmg` | The installer. This is the one you want. |
| `Lumi_universal.app.tar.gz` | The app archive the built-in updater downloads. |
| `Lumi_universal.app.tar.gz.sig` | Signature the updater verifies before installing. |
| `latest.json` | Update manifest the app reads to find new versions. |

Every update is signed, and Lumi refuses to install one whose signature doesn't
check out.

## Something broken?

Open an [issue](https://github.com/thiennguyen93/lumi-releases/issues) with your
macOS version, your Lumi version, and what you did before it went wrong.

This repository carries release artifacts only — no source.
