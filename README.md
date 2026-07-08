<div align="center">

# Open Atelier

**A local-first AI workspace for creatives.**

Multi-provider LLM conversations, directly inside your project files — no cloud accounts, no telemetry, nothing leaves your machine.

[Website](https://open-atelier.app) · [Download](https://open-atelier.app/dl) · [Docs](https://doc.open-atelier.app) · [Changelog](https://open-atelier.app/changelog)

</div>

---

## What it is

Open Atelier is a desktop app that puts an AI chat side-by-side with your actual files — not a browser tab disconnected from your work. Open a folder, ask a question, and the AI answers with citations back to your own content. Everything it reads and every credential it stores stays on your machine.

- **Multi-provider LLM chat** — OpenAI, Anthropic, Google Gemini, Mistral, Groq, Together AI, DeepSeek, xAI, OpenRouter, and Ollama (local models)
- **Workspace-aware** — indexes your project files and lets the AI search and cite them
- **File operations** — create, edit, rename, and delete files from the chat, including real Word/Excel/PowerPoint/PDF output and MP3 narration
- **Skills** — Markdown-defined instructions that shape how the AI behaves in a given workspace
- **Local-first** — SQLite on disk, encrypted credentials, no accounts, no sync, no tracking
- **Cross-platform** — macOS and Linux today, Windows planned

## Repositories

| Repo | What it is |
|---|---|
| [`open-atelier`](https://github.com/Open-Atelier-App/open-atelier) | The public source and releases for the desktop app |
| [`open-atelier-public-doc`](https://github.com/Open-Atelier-App/open-atelier-public-doc) | Source for [doc.open-atelier.app](https://doc.open-atelier.app) |
| [`open-atelier-public-website`](https://github.com/Open-Atelier-App/open-atelier-public-website) | Source for [open-atelier.app](https://open-atelier.app) |

## Tech stack

Tauri 2 desktop app — React 19 + TypeScript on the frontend, Rust + Tokio + SQLite on the backend. Each LLM provider is its own Rust module behind a common routing layer.

## License

AGPL-3.0. Contributions welcome — see the [contributing guide](https://doc.open-atelier.app/contributing).