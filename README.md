# React + TypeScript DevContainer Template

A VS Code DevContainer skeleton for React.js + TypeScript development.
Runs Node.js 20 LTS on Debian Bookworm inside a reproducible container.

## How to use

1. Clone this repository
2. Open the directory in VS Code
3. Click **Reopen in Container** (or run `Dev Containers: Reopen in Container` from the Command Palette)
   - The first run builds the Docker image; subsequent starts are fast.
4. Scaffold a new React project inside the terminal:
   ```sh
   # Vite (recommended — create-react-app is deprecated)
   npm create vite@latest my-app -- --template react-ts
   cd my-app && npm install
   npm run dev
   ```
5. Open <http://localhost:3000> in your browser

## Requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop/) (or Docker Engine on Linux)
- [VS Code](https://code.visualstudio.com/) with the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

