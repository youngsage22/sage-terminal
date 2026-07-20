# Changelog

All notable changes to SAGE Terminal are documented here.

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
Versioning follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.0] — 2026-07-19

### 🎉 Initial Release

SAGE Terminal launches as a colorful, GPU-accelerated Windows terminal built on top of the battle-tested Microsoft Terminal engine.

### Added

**Core terminal engine**
- Full GPU-accelerated text rendering via DirectX
- Tab bar with drag-to-reorder support
- Pane splitting — horizontal (`Alt+Shift+-`) and vertical (`Alt+Shift++`)
- Multiple window support
- Clickable URLs in terminal output
- Full Unicode, emoji, and CJK character rendering
- Cascadia Code font included (the best monospace font for terminals)
- Custom key binding support via `settings.json`
- Shell profiles: PowerShell, CMD, WSL2, Git Bash, fish, and any custom shell

**SAGE Branding & Themes**
- 🌑 **SAGE Dark** — clean, professional default theme  
  `background: #0d1117` · accent: `#a855f7`
- 🌈 **Rainbow** — vibrant, multi-color theme for maximum personality  
  `background: #0f0a1e` · accent: `#f472b6`
- 🌅 **Sunset** — warm amber tones for late-night sessions  
  `background: #1a0a00` · accent: `#f97316`
- 🔮 **SAGE Neon** — electric neon on deep black  
  `background: #0a0010` · accent: `#ff00ff`
- 🌊 **SAGE Ocean** — cool deep-blue palette  
  `background: #0a1628` · accent: `#00bfff`
- 🧛 **SAGE Dracula** — the beloved Dracula palette, SAGE edition  
  `background: #282a36` · accent: `#ff79c6`
- ❄️ **SAGE Nord** — minimal arctic tones  
  `background: #2e3440` · accent: `#88c0d0`
- 🤖 **SAGE Cyberpunk** — green-on-black matrix aesthetic  
  `background: #0d0208` · accent: `#00ff41`
- 🎨 **SAGE Monokai** — the classic Monokai Pro palette  
  `background: #272822` · accent: `#ae81ff`
- 🐱 **SAGE Catppuccin** — soft pastel Catppuccin Mocha  
  `background: #1e1e2e` · accent: `#cba6f7`
- ☀️ **SAGE Solarized Dark** — Ethan Schoonover's precision palette  
  `background: #002b36` · accent: `#268bd2`

**Brand documentation**
- `SAGE_TERMINAL.md` — full brand guide with color values and theme JSON
- `CONTRIBUTING.md` — setup guide and theme contribution instructions
- `SECURITY.md` — vulnerability reporting policy
- GitHub issue templates (bug report, feature request)
- GitHub Actions CI — validates JSON themes on every push

### Technical Foundation

Inherited from [microsoft/terminal](https://github.com/microsoft/terminal):
- `conhost.exe` — Windows Console Host
- Windows Terminal app (UWP / WinUI 3)
- `TerminalApp` — application layer
- `TerminalControl` — XAML control
- DirectX renderer, software renderer, and WDDM 1.x renderer
- VT sequence parser
- SSH and Telnet client support

---

## [Unreleased]

Things in progress for the next release:

- SAGE theme marketplace — browse and submit community themes
- One-click theme preview in the settings UI  
- Animated SAGE startup splash screen
- Theme export / share as URL
- Pre-built release `.msixbundle` binary

---

*Want to contribute? See [CONTRIBUTING.md](./CONTRIBUTING.md)*
