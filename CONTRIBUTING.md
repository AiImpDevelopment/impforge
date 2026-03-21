# Contributing to ImpForge AI Workstation

Thank you for your interest in contributing to ImpForge!

## Quick Start

```bash
git clone https://github.com/AiImpDevelopment/impforge
cd impforge/ImpForge
pnpm install
cargo tauri dev
```

## Tech Stack

- **Backend**: Rust (Tauri 2.10, 85+ commands)
- **Frontend**: Svelte 5 + TypeScript + TailwindCSS v4
- **UI**: bits-ui (Shadcn), Monaco Editor, xterm.js
- **Database**: SQLite (rusqlite, WAL mode)
- **AI**: Ollama, llama.cpp, HuggingFace Hub, FastEmbed
- **Browser**: chromiumoxide (CDP engine)

## Development Guidelines

1. Fork the repo and create a feature branch
2. Write tests for new functionality
3. Follow existing code style (rustfmt, prettier)
4. Submit a PR with a clear description

## Architecture

- `src-tauri/src/` — Rust backend (commands, orchestrator, agents)
- `src/routes/` — Svelte 5 pages (11 main routes)
- `src/lib/stores/` — Reactive state (17 stores)
- `src/lib/components/` — UI components (90+)

## License

MIT — see [LICENSE](LICENSE) for details.
