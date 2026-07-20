# SAGE Terminal — Dev Container

This folder configures a [Development Container](https://containers.dev/) for SAGE Terminal.

## What's included

| Tool | Purpose |
|------|---------|
| MSVC / C++ toolchain | Build the terminal from source |
| CMake | Build system |
| PowerShell | Default shell in the container |
| GitHub CLI | Push, PR, and release management |
| C++ IntelliSense | Full autocomplete and error highlighting in VS Code |
| GitLens | Advanced Git history and blame |

## How to use

### With GitHub Codespaces
1. Click **Code → Codespaces → Create codespace on main** on the repo page
2. Wait ~2 minutes for the container to build
3. Open `OpenConsole.sln` and start coding

### With VS Code Locally
1. Install [Docker Desktop](https://www.docker.com/products/docker-desktop/) and the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
2. Clone the repo: `git clone https://github.com/youngsage22/sage-terminal.git`
3. Open in VS Code: `code sage-terminal`
4. Click **Reopen in Container** when prompted

## Building from the container

```powershell
# Build the solution
msbuild OpenConsole.sln /p:Configuration=Release /p:Platform=x64

# Or use CMake
cmake -B build -S .
cmake --build build --config Release
```

> **Note:** Full builds require Windows. The container is configured for code editing, navigation, and theme/config work on any OS.
