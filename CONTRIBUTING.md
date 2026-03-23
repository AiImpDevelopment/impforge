# Contributing to ImpForge AI Workstation

Thank you for your interest in contributing to ImpForge!

## Tech Stack

- **Backend**: Rust (Tauri 2.10, 1,147 IPC commands)
- **Frontend**: Svelte 5 + TypeScript + TailwindCSS v4
- **UI**: bits-ui (Shadcn), BenikUI Theme Engine, xterm.js
- **Database**: SQLite (rusqlite, WAL mode)
- **AI**: Ollama (local), OpenRouter (cloud), FastEmbed
- **License**: Elastic License v2 (ELv2)

## Development Guidelines

1. Fork the repo and create a feature branch
2. Write tests for new functionality
3. Follow existing code style (rustfmt, prettier)
4. Submit a PR with a clear description

## Architecture

- `src-tauri/src/` — Rust backend (60+ modules, 1,147 commands)
- `src/routes/` — Svelte 5 pages (60 routes)
- `src/lib/stores/` — Reactive state (30 stores)
- `src/lib/components/` — UI components (167+)

## License

Elastic License v2 (ELv2) — see [LICENSE](LICENSE) for details.

---

Built by [AiImp Technology](https://github.com/AiImpDevelopment) (Karsten Schildgen, Germany)
