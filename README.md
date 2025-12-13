<p align="center">
  <img src="docs/images/Palks_Studio.png" alt="Palks Studio" width="600">
</p>

> 🇬🇧 English | [🇫🇷 Français](./README_FR.md)

![Made for VS Code](https://img.shields.io/badge/Editor-VS%20Code-blue.svg)
![Python](https://img.shields.io/badge/Python-3.x-yellow.svg)
![Platform](https://img.shields.io/badge/OS-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)
![License](https://img.shields.io/badge/License-LICENSE.txt-lightgreen.svg)

<p align="center">
  <a href="https://palks.gumroad.com/" target="_blank">
    <img src="https://img.shields.io/badge/Download%20on-Gumroad-orange?style=for-the-badge" alt="Download on Gumroad">
  </a>
  &nbsp;&nbsp;
  <a href="http://palks-studio.itch.io" target="_blank">
    <img src="https://img.shields.io/badge/Available%20on-Itch.io-blue?style=for-the-badge" alt="Available on Itch.io">
  </a>
  &nbsp;&nbsp;
  <a href="https://ko-fi.com/palksstudio" target="_blank">
    <img src="https://img.shields.io/badge/Buy%20on-Ko%E2%80%93fi-ff5f5f?style=for-the-badge" alt="Buy on Ko-fi">
  </a>
</p>

# VS Code – Formatting Pack (Lite Version)

**Version 1.1 — Public Demo**

A lightweight, read-only preview of the VS Code Formatting Pack by **Palks Studio**.

This Lite version provides a **passive and non-destructive environment**
designed to showcase the philosophy and structure of the full pack,
without modifying any files.

No formatting.
No cleanup.
No automation.

---

## Structure (Public version)

```
VSCode_Formatting_Pack/ (Lite Version)
├── README.md
│   ← Public documentation for the Lite version
│     (limited scope, no file modification)
│
├── LICENCE.txt
│   ← Proprietary license – Palks Studio
│
├── public_version/
│   └── .vscode/
│       ├── settings.json
│       │   ← Passive editor settings
│       │     - UTF-8 encoding
│       │     - LF line endings
│       │     - visual indentation (4 spaces)
│       │     - visible whitespace boundaries
│       │     - no automatic formatting
│       │
│       ├── keybindings.json
│       │   ← Single shortcut:
│       │     Alt + M → toggle the minimap
│       │
│       └── tasks.json
│           ← VS Code task (read-only):
│             - Margin detection
│             - analyzes whitespace and margins
│             - no file is ever modified
│
├── example_structure.txt
│   ← Overview of the full (Pro) version structure
│     and available features
│
└── docs/
    └── images/
        └── Palks_Studio.png
            ← Proprietary branding asset
```


The `.mp4` files in this folder (convert_lf.mp4, indent_clean.mp4, etc.) are intentionally included in the Lite version — they are real demonstrations from the full pack, showing its capabilities.

---

## What this Lite version does

- Applies **passive editor settings** for consistency and readability  

- Ensures:  

  - UTF-8 encoding  
  - LF line endings  
  - Visual indentation (4 spaces)  
  - Visible whitespace boundaries

- Provides a **read-only margin detection task**  
- Includes a minimal keyboard shortcut for navigation comfort

This version is intended for **evaluation and preview purposes only**.

---

## What this Lite version does NOT do

- No file formatting  
- No margin cleanup  
- No line ending conversion  
- No backups  
- No automatic actions on save  
- No project-wide transformations

All file modifications are **exclusive to the Pro version**.

---

## Included features

### Passive editor configuration

The provided `settings.json` applies neutral, predictable rules:  

- No automatic formatting  
- No formatter enforced  
- No language-specific automation  
- Identical behavior across Windows, macOS, and Linux

These settings are applied **locally to the project only**.

---

### Read-only margin detection

A single VS Code task is available:  

Terminal → Run Task → Margin detection (read-only)

This task:  

- Analyzes files for whitespace and margin issues  
- Reports findings in the terminal  
- **Never modifies any file**

It is intended to help you **observe** formatting issues,
not to fix them.

---

### Keyboard shortcut

- `Alt + M` → Toggle the minimap

No re-indentation or formatting shortcuts are included in this Lite version.

---

## Folder structure

The Lite package contains a minimal public setup:  

- `.vscode/`  
  - `settings.json` — passive editor settings  
  - `keybindings.json` — minimap toggle only  
  - `tasks.json` — read-only margin detection  
- `example_structure.txt`  
  - Overview of the full Pro version structure  
- `docs/images/`  
  - Palks Studio branding asset

---

## About the Pro version

The **Pro version** includes:  

- Margin cleanup (`clean.py`)  
- Line ending normalization (`convert.py`)  
- Read-only analysis and reporting (`space.py`)  
- Automatic backups on save (`backup.py`)  
- Multiple execution modes (global / active file / custom selection)  
- Full documentation and real usage examples

The Lite version is intentionally limited
to preserve a clear and honest boundary.
This ensures a transparent and predictable evaluation experience.

---

## Compatibility

- Visual Studio Code (recent versions)  
- Windows, macOS, Linux  
- No paid extensions  
- No external services  
- Works fully offline

---

## Credits & License

This pack is an original creation by **Palks Studio**.
Resale, redistribution or public modification without permission is prohibited.
Personal and professional use is allowed.

**Palks Studio**
Independent creator of useful, autonomous digital tools.

- GitHub: https://github.com/Palks-Studio  
- Gumroad: https://palks.gumroad.com  
- Itch.io: http://palks-studio.itch.io  
- Ko-fi: https://ko-fi.com/palksstudio  
- Twitter (X): https://x.com/Palks_Studio

---

## Signature

**Palks Studio — Version 1.1**  
Compatible with Visual Studio Code (Prettier disabled by default).
