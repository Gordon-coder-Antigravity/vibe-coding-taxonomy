# ⚡ Vibe Coding Architecture Taxonomy Explorer

> **An interactive architectural taxonomy and runtime explorer for vibe coding, agentic AI IDEs, CLI tools, and intent-driven software engineering.**

[![Deploy to GitHub Pages](https://github.com/your-username/vibe-coding-taxonomy/actions/workflows/deploy.yml/badge.svg)](https://github.com/your-username/vibe-coding-taxonomy/actions/workflows/deploy.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Vite](https://img.shields.io/badge/Vite-6.x-646CFF.svg)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-v3-38B2AC.svg)](https://tailwindcss.com/)
[![Chart.js](https://img.shields.io/badge/Chart.js-v4-FF6384.svg)](https://www.chartjs.org/)

---

## 🌟 Overview

The software engineering paradigm is transitioning from imperative syntax authors to specification designers and system architects. 

This web application categorizes and benchmarks modern AI coding platforms across two fundamental axes:
1. **Execution Environment**: Browser-Hosted Ephemeral Sandboxes vs. Local & Repo Worktrees.
2. **User Agency / Abstraction Level**: Zero-setup visual web builders to headless background agents.

---

## 🗺️ The 5 Architectural Layers

| Layer | Classification | Representative Platforms | Primary Runtime Environment |
| :--- | :--- | :--- | :--- |
| **Layer 1** | **Instant Web Builders** | Lovable, Bolt.new, v0 by Vercel, Replit Agent | WebAssembly / WebContainers / Cloud VMs |
| **Layer 2** | **AI-Native Desktop IDEs** | Google Antigravity, Cursor, Windsurf | Native File System, Git Worktrees, LSP |
| **Layer 3** | **CLI Shell Agents** | Claude Code, Aider, OpenCode | Terminal Shell, AST Indexer, Local Git Plumbing |
| **Layer 4** | **Open IDE Extensions** | Cline (Claude Dev), Roo Code, Continue | VS Code / JetBrains Plugin APIs, MCP Protocol |
| **Layer 5** | **Headless PR Agents** | Devin, Google Jules, GitHub Copilot Workspace | Isolated Cloud VMs, Headless Runners |

---

## ✨ Features

- 🧭 **Interactive Hierarchy Flowchart**: Visual breakdown from User Intent down to Tiers and Layers. Clicking any layer filters the runtime catalog instantly.
- 🔍 **Filterable Tool Directory**: Real-time multi-dimensional search across Layer, Runtime Tier, and Skill Entry Barrier for 16 leading tools.
- 📈 **Dynamic Global Telemetry Dashboard**: Time-series telemetry tracking active developer adoption numbers across Layers 1 to 5 using Chart.js with manual and auto-polling (5s) refresh.
- ⚖️ **Side-by-Side Comparison Matrix**: Select and benchmark up to 3 tools simultaneously across execution models, skill curves, and architectural strengths.
- 🧠 **Computer Science Trade-offs**: Deep analysis of Hallucination vs. Drift, Context Window vs. Token Cost, and Determinism vs. Stack Flexibility.
- 🎯 **Interactive Tool Decision Wizard**: A 3-question guided diagnostic providing tailored architectural recommendations based on user constraints.
- 📱 **Mobile & Desktop Responsive**: Built with a warm neutral slate & indigo palette, custom scrollbars, and accessible modal inspector dialogs.

---

## 🚀 Quick Start (Local Development)

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or higher recommended)

### 1. Install Dependencies
```bash
npm install
```

### 2. Start Local Development Server
```bash
npm run dev
```
Open your browser at `http://localhost:3000` to preview the app with instant Hot Module Replacement (HMR).

### 3. Build for Production
```bash
npm run build
```
The optimized static production bundle will be generated in the `dist/` directory.

### 4. Preview Production Build
```bash
npm run preview
```

---

## 🌐 Deploy to GitHub in 3 Easy Steps

### Step 1: Initialize Git Repository
In your project folder (`vibe-coding-taxonomy`), run:
```bash
git init
git add .
git commit -m "feat: initial commit of vibe coding taxonomy web app"
git branch -M main
```

### Step 2: Push to GitHub
1. Create a new repository on [GitHub](https://github.com/new) named `vibe-coding-taxonomy`.
2. Link your local repo and push:
```bash
git remote add origin https://github.com/<YOUR-USERNAME>/vibe-coding-taxonomy.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your GitHub repository: `Settings` → `Pages`.
2. Under **Build and deployment** > **Source**, select **GitHub Actions**.
3. That's it! The included [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) workflow will automatically build with Vite and publish your site at:
   ```
   https://<YOUR-USERNAME>.github.io/vibe-coding-taxonomy/
   ```

---

## ☁️ Alternative Deployments

This application is 100% static and zero-backend, making it compatible with all major static hosting platforms:

### Vercel
1. Import your GitHub repository into [Vercel](https://vercel.com).
2. Framework Preset: **Vite**.
3. Click **Deploy**.

### Netlify
1. Connect your repository on [Netlify](https://www.netlify.com).
2. Build command: `npm run build`
3. Publish directory: `dist`
4. Click **Deploy Site**.

---

## 📂 Project Structure

```
vibe-coding-taxonomy/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Pages CI/CD workflow
├── public/
│   └── favicon.svg             # App favicon
├── src/
│   ├── data/
│   │   └── taxonomy-data.js    # Data source (tools catalog & telemetry seeds)
│   ├── styles/
│   │   └── app.css             # Custom styles & animations
│   └── main.js                 # App state, Chart.js integrations & interactive logic
├── index.html                  # Semantic HTML5 entry point
├── package.json                # Dependencies and build scripts
├── vite.config.js              # Vite configuration (relative base for GitHub Pages)
├── .gitignore                  # Git ignore rules
├── LICENSE                     # MIT License
└── README.md                   # Project documentation
```

---

## 🤝 Contributing

Contributions are always welcome!
1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/NewTool`).
3. Commit your Changes (`git commit -m 'feat: add new tool to taxonomy'`).
4. Push to the Branch (`git push origin feature/NewTool`).
5. Open a Pull Request.

---

## 📄 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.
