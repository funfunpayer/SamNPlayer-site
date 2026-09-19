<p align="center">
  <img src="https://raw.githubusercontent.com/funfunpayer/SamNPlayer/main/docs/media/logo.png" alt="SamNPlayer mark" width="140" />
</p>

<h1 align="center">SamNPlayer</h1>

<p align="center">
  <strong>Generate · Play · Train</strong> — local desktop app for
  <code>.funscript</code> and SVAKOM Sam Neo&nbsp;2 / Neo&nbsp;2&nbsp;Pro
</p>

<p align="center">
  <img alt="Closed source" src="https://img.shields.io/badge/source-private-334155?style=flat-square" />
  <img alt="No Electron" src="https://img.shields.io/badge/GUI-~13%20MB%20native-0d9488?style=flat-square" />
  <img alt="Local only" src="https://img.shields.io/badge/AI-local%20optional-334155?style=flat-square" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/funfunpayer/SamNPlayer/main/docs/media/wordmark.png" alt="SamNPlayer wordmark" width="320" />
</p>

> **This page is the public showcase.** The application **source code is private**
> (team only). Visitors can learn what the product does and see the UI —
> they cannot fork or download the repository that builds it.

---

## Why SamNPlayer

Most tools in this space are either a **player**, a **generator**, or a
**heavy Electron shell**. SamNPlayer is one native desktop app that does
the full loop — and stays honest about what is measured vs. what is only
suggested.

| | Typical alternatives | **SamNPlayer** |
|---|---|---|
| App size | Electron often 100+ MB | **~13 MB** GUI (OS webview — no bundled Chromium) |
| Scope | Play *or* generate | **Play + generate + device + training** in one window |
| AI | Cloud, bundled weights, or AI-only scripts | **Optional local ONNX** — AI *proposes*, classical tracking *writes* the Funscript |
| Privacy | Telemetry / downloads common | **Local-only** — no model in the binary, no auto-download, no cloud calls |
| Device | Generic clients | **Sam Neo 2 first-class** (BLE + Intiface + Mock) with diagnostics |
| Quality | “Looks fine” | **Quality Doctor**, Script Doctor, golden-clip style checks — numbers before claims |

**What we deliberately do *not* do:** FunGen clones, silent AI Funscripts,
fashion UI rewrites, or cloud sync of your library.

---

## Screenshots

<p align="center">
  <img src="https://raw.githubusercontent.com/funfunpayer/SamNPlayer/main/docs/media/gui-generator.png" alt="Generator tab" width="900" />
  <br /><em>Generate</em> — ROI workflow, Tf/Tj, Quality Doctor on the rail
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/funfunpayer/SamNPlayer/main/docs/media/gui-playback.png" alt="Playback tab" width="900" />
  <br /><em>Playback</em> — script-alone or video-synced; heatmap & playlist
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/funfunpayer/SamNPlayer/main/docs/media/gui-player-rail.png" alt="Player with live meters" width="900" />
  <br />Live vibration / suction meters — curve & device run even without a film
</p>

---

## What you get

- **Playback** with real in-app video sync, heatmap, curve tools, playlist shuffle/repeat
- **Generator** with classical CV first; optional local AI ROI (never AI-only Funscripts)
- **Device** BLE / Intiface / Mock + diagnostics for Sam Neo 2
- **Training** tab (stop-start / plateau) with session history
- Native desktop (Wails), English UI, auto-update with checksums

---

## Downloads

Binaries are distributed by the team. Ask the maintainers for the current
Windows / Linux GUI or CLI build if you have access.

---

## Source access

| Who | What they get |
|-----|----------------|
| **Core team** | Private application repository (full source, CI, releases) |
| **Everyone else (e.g. Anna)** | **This showcase only** — no fork, no clone of the product source |

Contact the maintainers for a build or demo — there is no public `git clone`
of the application.

---

© 2026 funfunpayer · Product source: proprietary / private repository
