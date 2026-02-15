# Dev Container Template - Rust

Pre-configured containerized development environment for Rust applications.

## Features

- **Rust** with Cargo
- **rust-analyzer** for language server
- **clippy** for linting
- **LLDB** for debugging
- **GitLens** for Git integration
- **SQLTools** for database management

## Quick Start

1. Copy `.devcontainer` folder to your project root
2. Open the project in VS Code
3. Press `F1` and select **"Dev Containers: Reopen in Container"**

## Configuration

### Ports
- `3000` - Application server
- `8080` - Alternative HTTP port

### Extensions Included
- rust-analyzer
- LLDB
- Resource Romulator
- PowerShell
- Docker
- SQLTools
- IntelliCode
- GitLens

### Post-Create Commands
- Shows Cargo version
- Shows Rustc version
- Updates Rust toolchain

## Requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [VS Code](https://code.visualstudio.com/)
- [Dev Containers Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## License

MIT
