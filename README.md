<div align="center">

<img src="https://raw.githubusercontent.com/youngsage22/sage-terminal/main/banner.svg" alt="SAGE Terminal" width="100%" />

<br />

[![CI](https://github.com/youngsage22/sage-terminal/actions/workflows/ci.yml/badge.svg)](https://github.com/youngsage22/sage-terminal/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-a855f7.svg)](./LICENSE.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-f472b6.svg)](./CONTRIBUTING.md)
[![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D4?logo=windows&logoColor=white)](https://github.com/youngsage22/sage-terminal)
[![C++](https://img.shields.io/badge/C%2B%2B-17-00599C?logo=cplusplus&logoColor=white)](https://github.com/youngsage22/sage-terminal)
[![Stars](https://img.shields.io/github/stars/youngsage22/sage-terminal?style=social)](https://github.com/youngsage22/sage-terminal/stargazers)

<br />

### **The Windows terminal that finally has some color.**

*GPU-accelerated. Tabbed. Fully customizable. Vibrant by default.*

<br />

[**Download**](https://github.com/youngsage22/sage-terminal/releases) · [**Themes**](#-themes) · [**Report Bug**](https://github.com/youngsage22/sage-terminal/issues/new?template=bug_report.yml) · [**Request Feature**](https://github.com/youngsage22/sage-terminal/issues/new?template=feature_request.yml)

</div>

---

## Why SAGE Terminal?

The default Windows terminal is powerful — but visually, it's the color of cement. SAGE Terminal takes everything that makes Windows Terminal great and wraps it in a design that actually feels alive.

Three hand-crafted color themes. Rainbow accents out of the box. A terminal that makes you *want* to open it.

> "Your terminal should be as colorful as your code."

---

## 🎨 Themes

SAGE Terminal ships with **3 exclusive built-in themes** — ready to use from the first launch.

<table>
<tr>
<th>Theme</th>
<th>Vibe</th>
<th>Background</th>
<th>Accent</th>
<th>Best for</th>
</tr>
<tr>
<td><b>🌑 SAGE Dark</b></td>
<td>Clean, professional</td>
<td><code>#0d1117</code></td>
<td><code>#a855f7</code></td>
<td>All-day coding</td>
</tr>
<tr>
<td><b>🌈 Rainbow</b></td>
<td>Vibrant, playful</td>
<td><code>#0f0a1e</code></td>
<td><code>#f472b6</code></td>
<td>Standing out in screenshots</td>
</tr>
<tr>
<td><b>🌅 Sunset</b></td>
<td>Warm, focused</td>
<td><code>#1a0a00</code></td>
<td><code>#f97316</code></td>
<td>Late-night sessions</td>
</tr>
</table>

Switching themes:

```json
// In your SAGE Terminal settings.json
{
  "profiles": {
    "defaults": {
      "colorScheme": "Rainbow"
    }
  }
}
```

Want to add your own? [Submit a theme PR](./CONTRIBUTING.md#adding-a-theme) — they're fast-tracked.

---

## ✨ Features

Everything from **Windows Terminal**, plus SAGE's signature color treatment:

<table>
<tr>
<td width="50%">

**⚡ GPU-Accelerated Rendering**
Built on DirectX — buttery smooth text at any font size or scale.

**📑 Tabs & Panes**
Split your workspace horizontally or vertically. Drag to reorder tabs.

**🎨 3 Exclusive Themes**
SAGE Dark, Rainbow, and Sunset — each pixel-perfect and hand-crafted.

**🔤 Full Unicode + Emoji Support**
Every character renders correctly. Including 🦄.

</td>
<td width="50%">

**🔧 JSON Config**
Every setting is a JSON key. Version-control your terminal setup.

**🐚 Any Shell**
PowerShell, CMD, WSL2, Git Bash, fish — SAGE Terminal runs them all.

**🖥️ Multiple Windows**
Open as many SAGE Terminal windows as you need. Each with its own profile.

**🔗 Clickable URLs**
Links in your terminal output are clickable. Finally.

</td>
</tr>
</table>

---

## 🚀 Getting Started

### Option 1 — Download the Release *(recommended)*

Head to [**Releases**](https://github.com/youngsage22/sage-terminal/releases) and download the latest `.msixbundle`. Double-click to install.

### Option 2 — Build from Source

**Requirements:**
- Windows 10 (21H2+) or Windows 11
- Visual Studio 2022
  - Workload: **Desktop development with C++**
  - Workload: **Universal Windows Platform development**
  - Component: **Windows 11 SDK (10.0.22000.0)**

```powershell
# Clone
git clone https://github.com/youngsage22/sage-terminal.git
cd sage-terminal

# Open and build in Visual Studio
start OpenConsole.sln
# Build → Build Solution (F7)
# Debug → Start Debugging (F5)
```

Full build documentation: [BUILDING.md](./BUILDING.md)

---

## ⌨️ Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| New tab | `Ctrl + T` |
| Close tab | `Ctrl + W` |
| Split pane (horizontal) | `Alt + Shift + -` |
| Split pane (vertical) | `Alt + Shift + +` |
| Switch tab | `Ctrl + Tab` |
| Open settings | `Ctrl + ,` |
| Find | `Ctrl + Shift + F` |
| Fullscreen | `F11` |
| Copy | `Ctrl + C` |
| Paste | `Ctrl + V` |

---

## 🗺️ Roadmap

- [x] SAGE Dark, Rainbow, and Sunset themes
- [x] Full rebrand with custom branding guide (`SAGE_TERMINAL.md`)
- [x] Custom README, contributing guide, and support docs
- [ ] SAGE theme marketplace (submit & browse community themes)
- [ ] One-click theme preview in settings
- [ ] Animated startup splash with SAGE logo
- [ ] Theme export / share as URL
- [ ] Pre-built release binaries

Want to help build any of these? [See the contributing guide →](./CONTRIBUTING.md)

---

## 🤝 Contributing

SAGE Terminal welcomes all contributions. Read [CONTRIBUTING.md](./CONTRIBUTING.md) to get started.

Not sure where to start? Look for issues tagged [`good first issue`](https://github.com/youngsage22/sage-terminal/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

The easiest contribution: **submit a new color theme**. No C++ required — just a JSON file. [Instructions here.](./CONTRIBUTING.md#adding-a-theme)

---

## 🙏 Credits

SAGE Terminal is built on top of [Microsoft Terminal](https://github.com/microsoft/terminal) — an incredible open-source project by Microsoft and its contributors. The GPU rendering engine, tab system, pane splitting, and settings infrastructure are all their work. SAGE adds branding, color themes, and a friendlier face.

If you enjoy SAGE Terminal, [go star Microsoft Terminal too](https://github.com/microsoft/terminal) — they deserve it.

---

## 📄 License

[MIT](./LICENSE.md) — free to use, fork, modify, and redistribute.

---

<div align="center">

**If SAGE Terminal made your terminal a happier place, leave a ⭐**

Takes one second. Means a lot.

<br />

Built with 💜 by [youngsage22](https://github.com/youngsage22)

`★ Star` · [`🐛 Bug`](https://github.com/youngsage22/sage-terminal/issues/new?template=bug_report.yml) · [`🚀 Feature`](https://github.com/youngsage22/sage-terminal/issues/new?template=feature_request.yml) · [`🎨 Theme PR`](./CONTRIBUTING.md#adding-a-theme)

</div>
