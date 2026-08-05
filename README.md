# 🎹 Chord Chart

Render chord charts from iReal Pro links and simple text chord sheets inside Obsidian.

<img src="docs/screenshot.png" width="600" alt="Chord chart rendered in Obsidian">

## ✨ Features

- **iReal Pro** — paste an `irealb://` URL and get a faithful paper chart. Tap the key pill above the chart to transpose to any key in real time.
- **Chord sheets** — write charts in a plain text format inspired by [chordsheet.com](https://www.chordsheet.com) — one chord per bar, spaces separate bars
- **Dark mode** — paper automatically adapts to your Obsidian theme
- **Dark mode** — paper adapts to your Obsidian theme
- **BRAT** — install via [BRAT](https://github.com/TfTHacker/obsidian42-brat) with `leviyehonatan/obsidian-chord-chart`

## 📦 Install

**BRAT** (recommended): add `leviyehonatan/obsidian-chord-chart` in [BRAT](https://github.com/TfTHacker/obsidian42-brat) for auto-updates.

**Manual:** download the four files from the [repository](https://github.com/leviyehonatan/obsidian-chord-chart) (`main.js`, `manifest.json`, `styles.css`, `versions.json`) into `.obsidian/plugins/chord-chart/`.

## 🎵 Usage

### iReal Pro charts

Copy an `irealb://` URL from the iReal Pro app or online forums:

````markdown
```chart-ireal
irealb://Autumn%20Leaves=Kosma%20Joseph==Medium%20Swing=G%2D==1r34LbKcu7...
```
````

### Chord sheets

Write charts in a simple text format:

````markdown
```chart
= Verse
C Am F G
C Am F G

= Chorus
Am F C G
Am F G C
```
````

**Format rules:**
- One chord = one bar, spaces separate bars
- `_` splits a bar — `Dm7_G7` = two chords in one bar
- `:` section title · `=` section with double barline
- `-` text annotation · `1.` / `2.` volta endings
- `D.C.` da capo · `O` coda sign · `#` comments

## 🔒 Source

This plugin is **closed source**. The public repository contains only pre-built output files. The source code is private.

## 🎸 License

All rights reserved.
