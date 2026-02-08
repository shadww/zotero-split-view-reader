# <img src="addon/content/icons/svreader.svg" height="32" align="center" /> Split-View Reader

[![zotero target version](https://img.shields.io/badge/Zotero-8-green?style=flat-square&logo=zotero&logoColor=CC2936)](https://www.zotero.org)
[![Using Zotero Plugin Template](https://img.shields.io/badge/Using-Zotero%20Plugin%20Template-blue?style=flat-square&logo=github)](https://github.com/windingwind/zotero-plugin-template)

[English](README.md) | [简体中文](doc/README-zhCN.md)

---

**Split-View Reader** is a plugin for [Zotero 8](https://www.zotero.org/) that enables split-view reading with synchronized controls.

<p align="center">
  <img src="doc/example.png" width="90%" alt="Example" />
</p>

## Features

- **Split-View Mode**: View the same PDF document in two synchronized panes side by side
- **Synchronized Scrolling**: Scroll both views simultaneously for seamless reading
- **Independent Navigation**: Each pane can also be navigated independently when needed
- **Seamless Integration**: Works naturally within Zotero's reader interface

## Installation

1. Download the latest `.xpi` file from [Releases](https://github.com/zerolfl/zotero-split-view-reader/releases)
2. In Zotero, go to `Tools` → `Plugins`
3. Click the gear icon and select `Install Plugin From File...`
4. Select the downloaded `.xpi` file

## Usage

### Quick Start with Command Palette

Press `Shift + P` to open Zotero's command palette, then select **Split View Reader** to start split-view mode.

<img src="doc/command-example.png" width="80%" alt="Command Palette" />

### Right-Click Context Menu

Right-click in either pane to access these options:

| Option | Description |
|--------|-------------|
| **Close Split-View Reader** | Exit split-view mode |
| **Primary Window** | Set current pane as the primary (sync source) |
| **Open Another PDF** | Replace secondary pane with a different PDF |
| **Swap PDFs** | Swap the PDFs between left and right panes |
| **Sync Position & Zoom** | Manually sync position and zoom level |

<p align="left">
  <img src="doc/right-click1.png" width="18%" style="vertical-align: top" />
  <img src="doc/right-click2.png" width="23%" style="vertical-align: top" />
</p>

### Settings

Go to `Edit` → `Settings` → Click Split-View Reader to configure:

<img src="doc/svreader-setting.png" width="80%" alt="Settings" />
