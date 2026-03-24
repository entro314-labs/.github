# entro314 labs
**Indie AI Lab** — We explore emerging AI capabilities through rapid prototyping and real-world systems that actually ship.

```
┌─ entro314@labs ~/shipped
└─ $ git log --oneline --graph
* feat: ship Apple Intelligence SDK — on-device AI via Vercel AI SDK v6
* feat: ship VDK CLI v2 — train AI assistants on your codebase (@vdkit)
* feat: ship AI Context Schema — universal AI interop standard (@vdkit)
* feat: Entrolytics v2 — privacy-first analytics, 25+ SDKs (@entrolytics)
* feat: CapySquash platform — PostgreSQL migration optimization (@capysquash)
* feat: Go TUI tools → Homebrew tap (techtell, devkill, cool-kit, git-herd)
* feat: release AI changelog generator v2.5.1 — CLI + MCP server
* feat: ship FairRent ML to production (99.89% accuracy)
* feat: biome-to-oxc v0.8 — monorepo migration, plugin scaffolding
* feat: MCP ecosystem tools — icons generator, build action, slash agents
* feat: complete warm sunset accessible design system
* wip: HermesAI, Polaris AI, Sainni — AI application prototypes

┌─ entro314@labs ~/shipped
└─ $ echo "Making AI less terrible, one weekend at a time"
Making AI less terrible, one weekend at a time

┌─ entro314@labs ~/shipped
└─ $ █
```

## 🧪 Current Portfolio

### Flagship projects (public)

| Project | Status | Stack | Description |
|---------|--------|-------|-------------|
| **Tauri Apple Intelligence** | `🟢 Active` | `Rust · Swift · Tauri · Foundation Models` | Native Tauri commands for Apple Intelligence — streaming + tool calling on macOS 26+. ([GitHub](https://github.com/entro314-labs/tauri-apple-intelligence)) |
| **Apple Intelligence SDK** | `🟢 Active` | `TypeScript · AI SDK v6 · Provider` | Vercel AI SDK v6 provider with pluggable transports — fully on-device, no cloud, no API keys. ([GitHub](https://github.com/entro314-labs/apple-intelligence-sdk) · [npm](https://www.npmjs.com/package/@entro314labs/apple-intelligence-sdk)) |
| **AI Changelog Generator** | `🟢 Production` | `Node.js · CLI · MCP` | AI-powered changelog + release notes from Git history — CLI and MCP server, most AI providers. ([GitHub](https://github.com/entro314-labs/ai-changelog-generator) · [npm](https://www.npmjs.com/package/ai-github-changelog-generator-cli-mcp)) |
| **CC Slash Agents** | `🟢 Production` | `TypeScript · Claude Code` | Generate slash commands for Claude Code from agent definitions — multi-agent workflow scaffolding. ([GitHub](https://github.com/entro314-labs/cc-slash-agents) · [npm](https://www.npmjs.com/package/@entro314labs/cc-slash-agents)) |
| **Web Icons Generator** | `🟢 Production` | `Node.js · CLI · MCP` | All web app icons from one source image — framework-aware, doubles as MCP server + Claude Desktop extension. ([GitHub](https://github.com/entro314-labs/web-icons-generator-cli-mcp) · [npm](https://www.npmjs.com/package/@entro314labs/web-icons-generator-cli-mcp)) |
| **MCPB Build Action** | `🟢 Production` | `GitHub Actions · MCP` | GitHub Action for building MCP packages — manifest validation, artifact upload, multi-package-manager. ([GitHub](https://github.com/entro314-labs/mcpb-build-action)) |
| **Techtell** | `🟢 Active` | `Go · TUI · Workspace Analysis` | Scans a developer workspace and summarizes its tech DNA — languages, frameworks, package managers. ([GitHub](https://github.com/entro314-labs/techtell)) |
| **Devkill** | `🟢 Active` | `Go · TUI · Cross-Platform` | Finds and removes heavy build artifacts (`node_modules`, `.venv`, `.cache`) across ecosystems. ([GitHub](https://github.com/entro314-labs/devkill)) |
| **Cool Kit** | `🟢 Active` | `Go · CLI · Coolify · DevOps` | Complete Coolify deployment toolkit — local Docker + cloud provisioning (Azure, AWS, GCP, Hetzner, DO). ([GitHub](https://github.com/entro314-labs/cool-kit)) |
| **Git Herd** | `🟢 Active` | `Go · CLI · Git Automation` | Concurrent bulk Git fetch/pull across hundreds of repositories. ([GitHub](https://github.com/entro314-labs/git-herd)) |
| **Biome to Oxc** | `🟢 Active` | `TypeScript · CLI · Migration` | Migrates Biome configs to Oxc (oxlint + oxfmt) — rule mapping, monorepo support, plugin scaffolding. ([GitHub](https://github.com/entro314-labs/biome-to-oxc) · [npm](https://www.npmjs.com/package/biome-to-oxc)) |
| **Starlight Document Converter** | `🟢 Production` | `TypeScript · Astro · CLI` | Converts Word, HTML, RTF, Markdown to Astro Starlight format with AI content analysis. ([GitHub](https://github.com/entro314-labs/starlight-document-converter) · [npm](https://www.npmjs.com/package/@entro314labs/starlight-document-converter)) |
| **Tauri macOS Haptics** | `🟢 Active` | `Rust · Tauri · objc2` | Taptic Engine plugin for Tauri v2 — type-safe haptic feedback API. ([GitHub](https://github.com/entro314-labs/tauri-macos-haptics)) |
| **Modern Tauri Vite Template** | `🟢 Active` | `TypeScript · React 19 · Vite 8 · Rust 2024` | Production Tauri 2 scaffold with Tailwind v4 and modern defaults. ([GitHub](https://github.com/entro314-labs/modern-tauri-vite-template)) |
| **React Arc Tabs** | `🟢 Active` | `TypeScript · React · Next.js` | Arc-style animated tabs component. ([GitHub](https://github.com/entro314-labs/react-arc-tabs) · [npm](https://www.npmjs.com/package/@entro314labs/react-arc-tabs)) |
| **Ghostty Web** | `🟢 Active` | `TypeScript · xterm.js` | Ghostty terminal for the browser with xterm.js API compatibility. ([GitHub](https://github.com/entro314-labs/ghostty-web)) |
| **Git Trim** | `🟢 Active` | `Go · CLI · Git Cleanup` | Cleans up merged, squash-merged, and stray local Git branches. ([GitHub](https://github.com/entro314-labs/git-trim-go)) |
| **Update NG** | `🟢 Active` | `Go · TUI · System Updater` | System updater managing 80+ package managers and dev tools with parallel execution. ([GitHub](https://github.com/entro314-labs/update-ng)) |
| **Ember** | `🟢 Active` | `Go · TUI · USB · UEFI` | TUI for creating bootable Windows USB drives — GPT-first, smart ISO analysis. ([GitHub](https://github.com/entro314-labs/ember)) |
| **Ember2Go** | `🟢 Active` | `Go · TUI · Windows-to-Go` | Portable Windows USB installer for macOS. ([GitHub](https://github.com/entro314-labs/ember2go)) |

Go tools ship via [`homebrew-tap`](https://github.com/entro314-labs/homebrew-tap): `brew tap entro314-labs/tap`

### Core lab initiatives (mixed public/private)

| Initiative | Status | Scope |
|------------|--------|-------|
| **VDK (Vibe Dev Kit)** | `🟢 Production` | Train any AI coding assistant to understand your project like a senior dev. CLI + blueprints + oxlint plugin. ([GitHub @vdkit](https://github.com/vdkit)) |
| **AI Context Schema** | `🟢 Live` | Universal interoperability standard for AI development tools. ([GitHub @vdkit](https://github.com/vdkit/ai-context-schema)) |
| **FairRent Platform** | `🟡 Private Product Track` | ML-driven rental intelligence — 99.89% prediction accuracy (`fairrent`, `fairrent-web`, `fairrent-ml`) |
| **HermesAI** | `🟡 Private Product Track` | Newsroom AI platform — story monitoring, synthesis workflows, admin review (Next.js 16) |
| **Polaris** | `🟡 Private Product Track` | AI marketing platform — brand guardrails, content organization, prompt engineering for teams |
| **Sainni** | `🟡 Private Product Track` | Real-time AI sales assistant — Next.js 16 dashboard + Tauri v2 desktop + Go API gateway |
| **Domatio** | `🟡 Private Product Track` | Role-aware real estate platform — Next.js 16, tRPC, Drizzle, Neon |
| **Epafi** | `🟡 Private Product Track` | Smart contact management — AI deduplication, data enrichment, multi-source consolidation |
| **Dots & Bricks** | `🟡 Private Product Track` | Polyglot DevOps bootstrapper — AI-ready project blueprints, release automation |
| **Energy System** | `🔵 Research` | Framework-agnostic TypeScript library for energy-aware, neurodivergent-friendly application behavior |
| **LNX** | `🔵 Research` | Arch-based rolling-release distro — COSMIC desktop, developer/AI-enthusiast focus |
| **Warm Sunset Design** | `✅ Complete` | Accessible design token and theming system ([VS Code theme](https://github.com/idominikosgr/warm-sunset-vscode-theme)) |
| **Fund-Deck / MyRoomie** | `🟡 Private Product Track` | Investor presentation platform and data tooling |

### Across the ecosystem

Work that originated here but grew into standalone organizations:

| Organization | What it is |
|-------------|-----------|
| **[@entrolytics](https://github.com/entrolytics)** | Privacy-first web analytics platform — dual-database (PostgreSQL + ClickHouse), 100K events/sec, <1KB tracker, 25+ SDK packages across React, Vue, Svelte, Astro, Next.js, Go, Python, PHP, mobile. ([entrolytics.click](https://entrolytics.click)) |
| **[@vdkit](https://github.com/vdkit)** | Vibe Development Kit — VDK CLI, AI Context Schema, blueprints, oxlint plugin. Train AI assistants on any codebase. |
| **[@capysquash](https://github.com/capysquash)** | PostgreSQL migration squashing and optimization — CLI, API, VS Code extension, web studio. |
| **[@MarkdownKit](https://github.com/MarkdownKit)** | Markdown processing toolkit. |

Satellite SDK repos for Entrolytics ([entro-react](https://github.com/entro314-labs/entro-react), [entro-vue](https://github.com/entro314-labs/entro-vue), [entro-svelte](https://github.com/entro314-labs/entro-svelte), [entro-go](https://github.com/entro314-labs/entro-go), [entro-python](https://github.com/entro314-labs/entro-python), [entro-php](https://github.com/entro314-labs/entro-php), and more) are published from this org.

## 💼 What We Build

**AI Systems & Research**
* On-device AI implementations (Apple Intelligence, Foundation Models, local models)
* AI-powered developer automation (changelogs, MCP servers, Claude Code agents)
* AI application prototypes (newsroom, marketing, sales, real estate)
* AI tool interoperability standards (AI Context Schema)
* ML applications with real users and operational constraints

**Production Platforms**
* Privacy-first analytics infrastructure (Entrolytics, 25+ SDKs)
* Database migration optimization (CapySquash)
* Developer tools that teams actually adopt — shipped to Homebrew, npm, and Cargo
* Desktop applications (Tauri + Rust + Apple native)

**Research & Frameworks**
* Inclusive design systems and accessible theming
* Alternative productivity models for neurodivergent developers
* Human-centered AI interaction patterns
* MCP server tooling and AI agent workflow patterns

## 🛠️ Tech Stack

```
AI/ML          │ Apple Intelligence, Foundation Models, Vercel AI SDK, MCP, Claude API, Scikit-learn
Go             │ CLI/TUI tools (Bubble Tea, GoReleaser), system utilities, API gateways
TypeScript     │ AI SDK providers, framework SDKs, React components, Next.js 16 apps
Rust           │ Tauri plugins, native macOS bridges (objc2), Cargo crates
Python         │ ML pipelines, FastAPI services, data analysis
Swift          │ Foundation Models bridge, Apple Intelligence interop
Infrastructure │ Vercel, GitHub Actions, Docker, ClickHouse, PostgreSQL, Redis, npm, Cargo, Homebrew
Data Sources   │ Eurostat APIs, ECB APIs, Economic Indicators, Product Analytics
```

## 📊 Lab Snapshot

- Canonical org: [@entro314-labs](https://github.com/entro314-labs)
- Repository inventory: **76 total** · **43 public** · **33 private**
- Sister organizations: [@entrolytics](https://github.com/entrolytics) · [@vdkit](https://github.com/vdkit) · [@capysquash](https://github.com/capysquash) · [@MarkdownKit](https://github.com/MarkdownKit)
- **8+ published npm packages** — from AI SDK providers to MCP servers to migration CLIs
- **Homebrew tap** with formulas for Go tools: `brew tap entro314-labs/tap`
- Verified repo ↔ local folder mapping is maintained in [`.github/README.md`](../README.md)

## 📝 Recent Shipping Highlights

* Apple Intelligence SDK + Tauri plugin pair — on-device AI via Vercel AI SDK v6 with Rust native bridge, no cloud dependency
* VDK CLI v2 and AI Context Schema shipped under [@vdkit](https://github.com/vdkit) — AI assistant training and universal interop standard
* Entrolytics v2 architecture at [@entrolytics](https://github.com/entrolytics) — dual-database, 25+ SDK packages verified
* Go TUI tool suite shipped to Homebrew — `techtell`, `devkill`, `cool-kit`, `git-herd` in active release cycles
* `biome-to-oxc` v0.8 — monorepo support, import graph baseline, JS plugin scaffolding
* MCP ecosystem tools (`ai-changelog-generator`, `web-icons-generator`, `cc-slash-agents`) in production
* AI application prototypes advancing — HermesAI (newsroom), Polaris (marketing), Sainni (sales)
* CapySquash PostgreSQL migration platform at [@capysquash](https://github.com/capysquash)

## 🤝 Collaboration

**Open to:**
* AI integration work with real operational outcomes
* Developer tooling partnerships
* Analytics infrastructure consulting
* Accessibility-first product and design consulting

**Not interested in:**
* Generic chatbot clones
* AI-wash marketing projects
* Shipping theater without user value

## 🔗 Connect

* **GitHub**: [@entro314-labs](https://github.com/entro314-labs)
* **Email**: lab@entro314.com
* **Homebrew**: `brew tap entro314-labs/tap`
* **Project mapping index**: [`.github/README.md`](../README.md)

<sub>**entro314 labs** • Independent • Experimental • Pragmatic • Shipping Real Solutions</sub>

---

*Building AI tools that solve real problems, with a focus on developer experience, accessibility, and privacy-first approaches. From weekend prototypes to production systems serving real users.*
