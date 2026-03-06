# Proxxied — Issue Tracker

This repository is the public issue tracker for [Proxxied](https://proxxied.com), a TCG proxy printing tool.

## Reporting a Bug

Before opening an issue, please check if it has already been reported.

When filing a bug, include:
- What you were doing when the issue occurred
- What you expected to happen
- What actually happened
- Browser/OS (or if using the desktop app)
- Screenshots if applicable

## Requesting a Feature

Feature requests are welcome. Please describe:
- The problem you're trying to solve
- Your proposed solution (if any)

## Note

The Proxxied source code is proprietary and maintained in a private repository. This repo exists solely for community bug reports and feature requests.

---

## Features

### Card & Image Management
- **Decklist Import** — Paste a decklist (`1x Sol Ring`) or import from Archidekt and Moxfield URLs, MPC XML, or CSV files
- **Alternate Artwork Selector** — Browse all available Scryfall prints per card, with set grouping, favorites, and filter/sort options
- **MPC Autofill Integration** — Search MPC Autofill's art library by card name, filter by DPI/source/tags, and export a compatible XML
- **Upload Library** — Upload your own images (individual files or ZIP packs), link front/back pairs, and reuse across projects
- **Double-Faced Card (DFC) Support** — Both faces managed automatically; select artwork per face independently
- **Cardback Library** — Built-in and custom cardbacks; set a global default or assign per card
- **Token Support** — Auto-import linked tokens; search and replace independently
- **11 Languages** — English, Spanish, French, German, Italian, Portuguese, Japanese, Korean, Russian, Simplified and Traditional Chinese

### Visual Editing
- **Brightness, Contrast, Saturation** — Basic image adjustments
- **Darkening Modes** — None, darken all, contrast edges, or contrast full with threshold and edge width control
- **Enhancements** — Sharpness, pop/punch effect, noise reduction, gamma correction
- **Per-Card Bleed Override** — Fine-tune bleed and offset per card, per face
- **WebGL Rendering** — GPU-accelerated via PixiJS for smooth real-time preview

### Print Layout
- **Bleed Modes** — Generate bleed, trim existing bleed, or no bleed; auto-detects pre-bleeded images
- **Page Presets** — A4, A3, Letter, Tabloid, Legal, ArchA, ArchB, SuperB, A2, A1, or custom
- **Portrait / Landscape** — Toggle with swap button
- **Grid Configuration** — Adjustable columns, rows, and card spacing
- **Cut Guides** — Customizable color and width; edge bleed guides always black
- **Units** — Switch globally between inches and millimeters

### PDF & Export
- **Export Modes** — Fronts only, interleaved all, interleaved DFC/custom only, duplex (fronts + mirrored backs), backs only, or visible faces
- **High-Resolution** — 1200 DPI output with precise crop marks
- **Silhouette Cameo** — SVG cutting templates and registration marks for Silhouette Studio
- **ZIP Export** — All card images in a single archive
- **MPC Autofill XML** — Export directly for MPC ordering
- **Decklist Copy/Download** — Plain text or with MPC art IDs preserved

### Project & Deck Management
- **Multi-Project Support** — Create, rename, switch, and delete projects; last project remembered
- **Sharing** — Share a project via a unique URL token
- **Drag & Drop Reordering** — Rearrange cards in the grid
- **Multi-Select** — Select multiple cards for bulk actions
- **Filter & Sort** — By color, mana cost, type, rarity, or custom back; alphabetical sort for export
- **Undo / Redo** — Full history stack

### App
- **Electron Desktop** — Native app for Windows, macOS, and Linux with auto-update
- **PWA** — Installable as a web app; works offline
- **Dark & Light Mode** — Matches system preference; PDF always exports on white
- **Keyboard Shortcuts** — Full keyboard support with a shortcuts reference panel
- **Responsive** — Mobile-friendly with pull-to-refresh

---
