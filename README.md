# Markdown Editor

A clean, distraction-free markdown editor with dual editing modes — switch between a rich WYSIWYG preview and raw markdown whenever you want. Works as a native desktop app on Windows, macOS, and Linux.

![Markdown Editor](https://img.shields.io/badge/version-0.9.4-blue)

---

## Download

Get the latest version from the [Releases page](../../releases/latest).

| Platform | Download |
|----------|----------|
| **Windows** | [Markdown-Editor-Setup-0.9.4.exe](../../releases/latest/download/Markdown-Editor-Setup-0.9.4.exe) |
| **macOS (Apple Silicon)** | [Markdown-Editor-0.9.4-arm64.dmg](../../releases/latest/download/Markdown-Editor-0.9.4-arm64.dmg) |
| **macOS (Intel)** | [Markdown-Editor-0.9.4.dmg](../../releases/latest/download/Markdown-Editor-0.9.4.dmg) |
| **Linux** | [Markdown-Editor-0.9.4.AppImage](../../releases/latest/download/Markdown-Editor-0.9.4.AppImage) |

---

## Features

### Dual Editing Modes
- **Preview mode** — WYSIWYG editing with a formatting toolbar
- **Raw mode** — Full markdown source with syntax highlighting (CodeMirror)
- Switch seamlessly between modes — content stays in sync

### Rich Formatting
- Bold, italic, strikethrough, highlight
- Headings (H1–H6)
- Links and images (with resize)
- Tables
- Task lists / checkboxes
- Subscript and superscript

### File Management
- Open, Save, Save As with native file dialogs
- New File with unsaved-changes protection
- Dirty-state indicator (`●`) in the title bar
- Prevents accidental data loss on close/quit

### Auto-Updates
- The app checks for updates on launch
- Downloads new versions in the background
- Installs automatically when you close the app — no manual re-download needed

---

## Installation

### Windows
1. Download the `.exe` installer
2. Run it — Windows SmartScreen may warn you (the app is unsigned)
3. Click **"More info"** → **"Run anyway"**
4. The app installs and creates a Start Menu shortcut

### macOS
1. Download the `.dmg` file (Apple Silicon or Intel, depending on your Mac)
2. Open the `.dmg` and drag the app to Applications
3. On first launch, right-click the app → **Open** (to bypass Gatekeeper since the app is unsigned)

### Linux
1. Download the `.AppImage` file
2. Make it executable: `chmod +x Markdown-Editor-0.9.4.AppImage`
3. Run it: `./Markdown-Editor-0.9.4.AppImage`

---

## FAQ

**Why does Windows show a security warning?**
The app is not code-signed. Windows SmartScreen flags any unsigned software. Click "More info" → "Run anyway" to proceed. The app is safe.

**Why does macOS block the app?**
Same reason — unsigned. Right-click → Open on first launch to allow it.

**How do I get updates?**
Updates are automatic. When a new version is available, the app downloads it in the background and installs it the next time you close the app.

**Where are my files saved?**
Files are saved wherever you choose via the Save/Save As dialog. The app also auto-saves your current work so nothing is lost if you forget to save.

---

## Report Issues

Found a bug or have a feature request? [Open an issue](../../issues/new).

---

## License

Free to use for personal and commercial purposes. The author reserves the right to change the licensing terms at any time.
