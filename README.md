# Local ZIP Archiver

> A fast, privacy-first web tool for creating and extracting ZIP archives entirely in the browser.

<p align="center">
  <img src="https://img.shields.io/badge/Vue.js-3-4FC08D?logo=vue.js" />
  <img src="https://img.shields.io/badge/JSZip-Compression-FF6C37?logo=javascript" />
  <img src="https://img.shields.io/badge/HTML5-Frontend-E34F26?logo=html5" />
  <img src="https://img.shields.io/badge/CSS3-Styling-1572B6?logo=css3" />
  <img src="https://img.shields.io/badge/Privacy-First-2ea44f?logo=shield" />
</p>

---

## Features

| Feature | Description |
|---------|-------------|
| 📦 **Create ZIP Archives** | Pack files and folders into a ZIP with drag & drop or file picker. |
| 📂 **Extract ZIP Archives** | Browse and extract contents of any ZIP file locally in your browser. |
| 🗂️ **Tree View** | Visual folder/file tree with expandable folders for easy navigation. |
| 🖱️ **Context Menu** | Right-click any file to download or delete it instantly. |
| 📥 **Bulk Download** | Download all extracted files as a single ZIP archive. |
| 📊 **Live Progress** | Real-time progress bar during compression and decompression. |
| 🔒 **Privacy First** | All processing happens client-side — files never leave your browser. |
| 📱 **Fully Responsive** | Optimized for desktop, tablet, and mobile screens. |

---

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or build tools required — runs entirely client-side

---

## Usage

### 1️⃣ Open the Tool
Simply open `zip_tool.html` in your browser — no installation needed.

### 2️⃣ Create an Archive
- Switch to the **Create Archive** tab
- **Drag & drop** files or folders, or use the **Select Files** / **Select Folder** buttons
- Review the file tree that appears
- Enter an archive name (optional)
- Click **Create ZIP** and save the resulting archive

### 3️⃣ Extract an Archive
- Switch to the **Extract Archive** tab
- **Drag & drop** a ZIP file, or use the **Select ZIP** button
- Browse the contents in the interactive tree view
- Right-click any file for quick **Download** or **Delete**
- Click **Download All** to save the entire contents as a new ZIP

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| **Framework** | Vue.js 3 (Global Build) |
| **Compression** | JSZip 3.10+ |
| **File Saving** | FileSaver.js 2.0+ |
| **Markup** | HTML5 |
| **Styling** | CSS3 (Flexbox, Grid, Media Queries) |
| **Design** | Custom responsive UI with no external CSS frameworks |

---

## Project Structure

```
zip_tool/
├── zip_tool.html
└── vue_global.js
```

---

## Highlights

- **Zero Server** — Everything runs in the browser; no backend or uploads required.
- **Privacy Guaranteed** — Your files are never sent to any server.
- **Folder Support** — Native folder selection via `webkitdirectory` with full path preservation.
- **Interactive Tree** — Expandable folder structure with context-menu actions.
- **Smooth UX** — Drag & drop zones, animated progress bars, and responsive layout.
- **Lightweight** — Minimal footprint with only Vue, JSZip, and FileSaver as dependencies.

---

## Author

Built by **[Tim](https://github.com/tim-fullstack-programmer)**  

---

<p align="center"><b>⭐ Star this repo if you found it useful!</b></p>
