<div align="center">

# 🌈 SAGE Terminal

<img src="https://img.shields.io/badge/SAGE-Terminal-blueviolet?style=for-the-badge&logo=windows-terminal&logoColor=white" />
<img src="https://img.shields.io/badge/Windows-Terminal-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/Built_With-C%2B%2B-F34B7D?style=for-the-badge&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/Platform-Windows-00BCF2?style=for-the-badge&logo=microsoft&logoColor=white" />

<br/>

![SAGE Terminal Banner](https://github.com/microsoft/terminal/assets/91625426/333ddc76-8ab2-4eb4-a8c0-4d7b953b1179)

<br/>

> **A vibrant, colorful, and powerful terminal experience for Windows.**  
> _SAGE Terminal_ is a modern, feature-rich terminal built for developers who want speed, style, and total control.

<br/>

[![🟣 Build Status](https://img.shields.io/badge/Build-Passing-brightgreen?style=flat-square&logo=github-actions)](https://github.com/youngsage22/sage-terminal)
[![🔵 License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](./LICENSE)
[![🟠 Version](https://img.shields.io/badge/Version-1.0.0-orange?style=flat-square)](https://github.com/youngsage22/sage-terminal/releases)
[![🟡 Stars](https://img.shields.io/github/stars/youngsage22/sage-terminal?style=flat-square&color=yellow)](https://github.com/youngsage22/sage-terminal/stargazers)
[![🟢 Forks](https://img.shields.io/github/forks/youngsage22/sage-terminal?style=flat-square&color=green)](https://github.com/youngsage22/sage-terminal/network)
[![🔴 Issues](https://img.shields.io/github/issues/youngsage22/sage-terminal?style=flat-square&color=red)](https://github.com/youngsage22/sage-terminal/issues)

</div>

---

## 🎨 What is SAGE Terminal?

**SAGE Terminal** is a colorful, modern terminal application for Windows that puts the *wow* back into your command line. With full Unicode support, GPU-accelerated text rendering, and a deeply customizable color palette, SAGE Terminal is the terminal your workflow deserves.

This repository contains the source code for:

| 🟣 Project | 📄 Description |
|---|---|
| **SAGE Terminal** | The main colorful terminal app |
| **SAGE Terminal Preview** | Cutting-edge preview builds |
| **Console Host** (`conhost.exe`) | The classic Windows console host |
| **Shared Components** | Shared between both projects |
| **ColorTool** | Set your console colors easily |
| **Sample Projects** | How to consume Windows Console APIs |

---

## 🌈 Color Palette & Themes

SAGE Terminal ships with a curated set of vibrant themes:

| 🎨 Theme | Description |
|---|---|
| 🟣 **SAGE Purple** | Deep violet tones, signature look |
| 🔵 **Ocean Blue** | Cool, calm, focused blues |
| 🟠 **Sunset Orange** | Warm amber and coral tones |
| 🟢 **Forest Green** | Natural, eye-friendly greens |
| 🔴 **Ruby Red** | Bold, confident, energetic |
| 🌈 **Rainbow Mode** | Full spectrum — cycle through all colors |
| ⚫ **Midnight Dark** | Pure dark with neon accents |
| ⚪ **Arctic Light** | Clean light mode with soft colors |

---

## ⚡ Key Features

```
 ███████╗ █████╗  ██████╗ ███████╗    ████████╗███████╗██████╗ ███╗   ███╗
 ██╔════╝██╔══██╗██╔════╝ ██╔════╝    ╚══██╔══╝██╔════╝██╔══██╗████╗ ████║
 ███████╗███████║██║  ███╗█████╗         ██║   █████╗  ██████╔╝██╔████╔██║
 ╚════██║██╔══██║██║   ██║██╔══╝         ██║   ██╔══╝  ██╔══██╗██║╚██╔╝██║
 ███████║██║  ██║╚██████╔╝███████╗       ██║   ███████╗██║  ██║██║ ╚═╝ ██║
 ╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚══════╝       ╚═╝   ╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝
```

- 🎨 **Vivid Multi-Color Themes** — choose from dozens of built-in color schemes or build your own
- ⚡ **GPU-Accelerated Rendering** — buttery-smooth text at any size
- 🗂️ **Tabbed Interface** — run multiple terminals side-by-side
- 🔤 **Full Unicode & Emoji Support** — display any character, anywhere
- 🖱️ **Rich Mouse Interaction** — click, scroll, select with precision
- 🔍 **Fuzzy Search** — `Ctrl+Shift+F` to search your scrollback
- 🎛️ **Profiles** — per-shell color schemes, fonts, and settings
- 📐 **Pane Splitting** — horizontal and vertical splits in one window
- 🌐 **WSL & SSH Ready** — connect to Linux and remote machines seamlessly
- ⌨️ **Fully Remappable Keybindings** — your terminal, your rules

---

## 🚀 Installation

### ✅ Recommended: Microsoft Store
<a href="https://aka.ms/terminal"><img src="https://img.shields.io/badge/Get%20It%20On-Microsoft%20Store-0078D6?style=for-the-badge&logo=microsoft&logoColor=white" /></a>

### 📦 Other Methods

**Via winget:**
```powershell
winget install --id Microsoft.WindowsTerminal -e
```

**Via Chocolatey:**
```powershell
choco install microsoft-windows-terminal
```

**Via Scoop:**
```powershell
scoop install windows-terminal
```

**Via GitHub Releases:**
Download the latest `.msixbundle` from the [Releases page](https://github.com/youngsage22/sage-terminal/releases).

---

## 🛠️ Building from Source

### Prerequisites

```
🟣 Visual Studio 2022 or later (with C++ Desktop workload)
🔵 Windows 11 SDK (10.0.22621.0 or higher)
🟠 .NET Framework 4.8 SDK
🟢 NuGet Package Manager
```

### Build Steps

```powershell
# Clone the repo
git clone https://github.com/youngsage22/sage-terminal.git
cd sage-terminal

# Build in PowerShell
Import-Module .\tools\OpenConsole.psm1
Set-MsBuildDevEnvironment
Invoke-OpenConsoleBuild

# Or build in Cmd
.\tools\razzle.cmd
bcz
```

---

## 🎮 Quick Start

Once installed, open SAGE Terminal and try these color-packed commands:

```bash
# Check your shell
echo $SHELL

# List with color
ls --color=auto

# View system info
neofetch

# Open htop for a colorful process viewer
htop
```

---

## 📖 Documentation

| 📚 Resource | 🔗 Link |
|---|---|
| Official Terminal Docs | [docs.microsoft.com/windows/terminal](https://docs.microsoft.com/windows/terminal) |
| Customization Guide | [doc/user-docs/](./doc/user-docs/) |
| Profiles & Settings | [doc/user-docs/](./doc/user-docs/) |
| Keybinding Reference | [doc/user-docs/](./doc/user-docs/) |
| Building the Code | [doc/building.md](./doc/building.md) |
| Contributing Guide | [CONTRIBUTING.md](./CONTRIBUTING.md) |

---

## 🤝 Contributing

We ❤️ contributions! Whether it's a bug fix, a new theme, or a brand-new feature — your work makes SAGE Terminal better for everyone.

Please read our [Contributing Guide](./CONTRIBUTING.md) and [Code of Conduct](./CODE_OF_CONDUCT.md) before submitting a pull request.

```
🔴 Step 1 — Fork this repo
🟠 Step 2 — Create a feature branch  (git checkout -b feature/amazing-colors)
🟡 Step 3 — Commit your changes      (git commit -m 'Add rainbow theme')
🟢 Step 4 — Push to your branch      (git push origin feature/amazing-colors)
🔵 Step 5 — Open a Pull Request      🎉
```

---

## 🛡️ Security

If you discover a security vulnerability, please follow responsible disclosure. See [SECURITY.md](./SECURITY.md) for details. Do **not** open a public issue.

---

## 📜 License

SAGE Terminal is released under the **[MIT License](./LICENSE)**.

The original source code is from the [Microsoft Terminal project](https://github.com/microsoft/terminal), used and adapted under the MIT License.

---

<div align="center">

**Made with 🌈 by [youngsage22](https://github.com/youngsage22)**

<img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=flat-square" />
<img src="https://img.shields.io/badge/Hacktoberfest-Friendly-orange?style=flat-square" />
<img src="https://img.shields.io/badge/Maintained-Yes-blue?style=flat-square" />

_If SAGE Terminal saved you time or made your workflow more colorful, give it a ⭐ — it means a lot!_

</div>
