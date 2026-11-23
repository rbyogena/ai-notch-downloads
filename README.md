# AI Notch — Windows downloads

**AI Notch** is a compact Windows desktop notch with animated dot-matrix eyes.

This public repository is **only for downloads and update packages**. The application's source code is stored separately in a private repository; no source code or private build credentials are published here.

## Download and install

**Official release page:** [AI Notch for Windows](https://github.com/rbyogena/ai-notch-downloads/releases)

**Release status:** No public installer has been released yet. The current preview is for private testing only. The link above will offer a Windows setup installer after the first approved, signed release is published.

Once that installer is available, download the Windows `Setup.exe`, run it once, and use AI Notch normally. Do not download a repository ZIP or the source code.

## Automatic updates

AI Notch checks this repository's **published GitHub Releases** for signed Windows update packages. Approved updates can be downloaded in the background and applied after an idle period, avoiding interruptions during full-screen use.

The update system uses Velopack and its `win` release channel. The official publishing workflow places installer binaries, release packages, and the `releases.win.json` update index **as release assets**, not as ordinary files in this repository.

**Automatic updates are not active until the first valid release is published and an installed-version-to-new-version test succeeds.** A README by itself does not activate the updater.

## Security and privacy

- This repository contains no private source code or GitHub write tokens.
- Stable public releases must pass the owner's release approval and Windows code-signing requirements.
- An unsigned private test installer is **not** an official public release.
- Never download or run an unexpected installer from an unverified link.

For current information and future official downloads, use the [Releases page](https://github.com/rbyogena/ai-notch-downloads/releases).
