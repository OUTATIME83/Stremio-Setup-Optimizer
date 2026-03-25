# Stremio Setup Optimizer ✨

A compact, client‑side wizard that generates preconfigured Stremio addon manifests and one‑click install links for debrid setups.

[<a href="https://outatime83.github.io/Stremio-Setup-Optimizer/" target="_blank" rel="noopener noreferrer">Open hosted version</a>]
---

## Overview

- Generates ready‑to‑install `stremio://` manifests configured from your preferences and debrid token.
- Provides guided presets (speed, coverage) and a Free (no‑debrid) mode.

## Supported

- Scrapers: Torrentio, Sootio, MediaFusion
- Catalogs: TMDB Collections, Streaming Catalogs, Trakt, IMDb Catalogs
- Utilities: OpenSubtitles PRO, SubSense, Statusio

## Free (No‑Debrid)

- Select **Free (No Debrid)** in Step 2 — no API key required.
- Uses public Torrentio instances (peer‑sourced streams): expect slower starts and variable quality.

## How it works

- The wizard builds a manifest configuration, injects the selected debrid token into the correct field (when applicable), encodes the JSON into the addon URL, and exposes a `stremio://` install link.

## Usage

Download/open `index.html` locally and follow the on‑screen wizard to configure and generate install links.

## Quick start

1. Download the repo or open `index.html` in your browser.
2. Follow the wizard: select debrid provider, paste API key (or choose Free), choose presets, generate the manifest.
3. Click the generated `stremio://` link to install in Stremio.

## Security & privacy

- Runs entirely in the browser; this repo does not send or store your API key.
- Generated manifest URLs embed the token in the path to support preconfigured installs — if you prefer, copy/download the manifest JSON and install it manually.

## Compatibility

- Tested on Windows 11 (Microsoft Edge).
- May work on other platforms, but I have only tested on the above platform/browser. If opening via `file://` causes issues, serve the folder over HTTP.
- If a manifest fails to install, I cannot help unless you open an issue with the generated manifest URL (redact tokens), browser & OS, and reproduction steps.

## Report issues / Get help

If you find a bug or have a suggestion, please open an issue on the repository Issues page: <a href="https://github.com/outatime83/Stremio-Setup-Optimizer/issues" target="_blank" rel="noopener noreferrer">https://github.com/outatime83/Stremio-Setup-Optimizer/issues</a>

When filing an issue, include:

- **Steps to reproduce** (what you clicked and expected vs actual)
- **Browser & OS** (e.g., Chrome on Windows 11)
- **Generated manifest URL** or a copy of the manifest JSON (redact API keys/tokens — do NOT paste secrets)
- **Screenshots** or console logs, if available

For privacy: never paste your API key or full token in issues — instead redact or replace it with `<REDACTED>`.

---

Made for fast, reliable streaming.
