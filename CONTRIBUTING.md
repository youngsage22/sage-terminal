# Contributing to SAGE Terminal 🎨

Thank you for wanting to make SAGE Terminal even better! This guide will get you set up.

---

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Ways to Contribute](#ways-to-contribute)
- [Development Setup](#development-setup)
- [Adding a Theme](#adding-a-theme)
- [Commit Style](#commit-style)

---

## Code of Conduct

Be respectful and welcoming. No harassment, gatekeeping, or toxicity.

---

## Ways to Contribute

| Type | How |
|------|-----|
| 🐛 Bug report | [Open a bug issue](https://github.com/youngsage22/sage-terminal/issues/new?template=bug_report.yml) |
| 🚀 Feature idea | [Open a feature request](https://github.com/youngsage22/sage-terminal/issues/new?template=feature_request.yml) |
| 🎨 New theme | Submit a PR with your JSON color scheme |
| 📝 Docs | Fix typos, improve explanations, add examples |
| 🔧 Code | Pick a `good first issue` from the issues tab |

---

## Development Setup

SAGE Terminal is built on top of Microsoft Terminal (C++/WinUI 3). To build from source you'll need:

**Requirements:**
- Windows 10/11 (64-bit)
- Visual Studio 2022 with workloads:
  - Desktop development with C++
  - Universal Windows Platform development
  - Windows 11 SDK (10.0.22000.0 or later)
- Git for Windows

**Build steps:**
```powershell
# Clone the repo
git clone https://github.com/youngsage22/sage-terminal.git
cd sage-terminal

# Open the solution
start OpenConsole.sln

# In Visual Studio: Build → Build Solution (F7)
# Run: Debug → Start Debugging (F5)
```

For detailed build instructions, see [BUILDING.md](./BUILDING.md) (inherited from the upstream Microsoft Terminal project).

---

## Adding a Theme

Themes are JSON color schemes. The easiest contribution!

1. Open `SAGE_TERMINAL.md` to see the existing themes
2. Create a new JSON file in `src/cascadia/TerminalApp/ColorSchemes/`
3. Follow this structure:

```json
{
  "name": "Your Theme Name",
  "background": "#0d1117",
  "foreground": "#e6edf3",
  "cursorColor": "#f472b6",
  "black": "#484f58",
  "red": "#ff7b72",
  "green": "#3fb950",
  "yellow": "#d29922",
  "blue": "#58a6ff",
  "purple": "#bc8cff",
  "cyan": "#39c5cf",
  "white": "#b1bac4",
  "brightBlack": "#6e7681",
  "brightRed": "#ffa198",
  "brightGreen": "#56d364",
  "brightYellow": "#e3b341",
  "brightBlue": "#79c0ff",
  "brightPurple": "#d2a8ff",
  "brightCyan": "#56d4dd",
  "brightWhite": "#f0f6fc"
}
```

4. Add a preview to `SAGE_TERMINAL.md`
5. Submit a PR — themed contributions are fast-tracked!

---

## Commit Style

```
type(scope): short description

Types: feat | fix | theme | docs | chore | refactor
Scope: terminal | themes | settings | rendering | (optional)

Examples:
  theme: add Ocean Breeze color scheme
  fix(rendering): correct cursor blink on high-DPI displays
  feat(tabs): add drag-to-reorder tab support
```

---

Thanks for contributing! ⭐ Stars help more developers find this project — every one counts.
