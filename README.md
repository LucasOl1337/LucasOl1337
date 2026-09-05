### Hi, I'm Lucas 👋

**Software engineer who builds products and tools with AI agents**, based in São Paulo, Brazil.

Two kinds of work, one method. At NexUnio I ship production software for clients. In public I ship the tools I need to work with several agents at once. In both, I write the brief, split the work, run builders and reviewers as separate agents (Codex, Claude Code, Grok, Hermes), and own the product decisions, integration, testing and final result.

#### 🧰 Tools for working with AI agents

- **[RamDog](https://github.com/LucasOl1337/RamDog)** — process manager for Windows, Linux and macOS, in Rust. Groups processes by the app that started them, shows origin and categories, tree kill and locks. [v0.9.0](https://github.com/LucasOl1337/RamDog/releases/tag/v0.9.0) ships packages for all three systems.
- **[KamuiT](https://github.com/LucasOl1337/kamuit)** — native terminal workspace for AI agents (Grok, Claude, Codex, Pi): Windows Terminal core on Windows, GTK4 + VTE on Linux, with CLI, IPC and MCP so agents can open their own tabs.
- **[Estúdio](https://github.com/LucasOl1337/estudio)** — Rust window over an image-generation pipeline: references, use cases, Codex or Grok batches, live progress and previous results in one place.
- **[The Last Arrow](https://github.com/LucasOl1337/The-Last-Arrow)** — Unity/C# arena where external LLM agents receive game state and act through a Python broker, with persistent bot profiles and observability overlays.
- **[ChessCam](https://github.com/LucasOl1337/ChessCam)** — real-time multiplayer chess: WebSocket netcode, server-validated moves, reconnect handling and match review. A model timeout pauses the match instead of inventing a move.

#### 🐧 Linux / Omarchy

I moved my daily setup to Omarchy (Arch + Hyprland) in September 2026 and started shipping what I was missing:

- **[Sussurro](https://github.com/LucasOl1337/sussurro)** — local dictation for Windows and Linux: Silero VAD + faster-whisper on CUDA, text typed or pasted where the cursor is. No audio leaves the machine. [v0.3.0](https://github.com/LucasOl1337/sussurro/releases/tag/v0.3.0) · [site](https://lucasol1337.github.io/sussurro/)
- **[Ponte](https://github.com/LucasOl1337/ponte)** — touch controls and live monitor views for an Omarchy desktop from an Android phone, over Tailscale. Experimental alpha, verified on a real device. [project page](https://lucasol1337.github.io/ponte/)
- **[Magma](https://github.com/LucasOl1337/magma-lights)** — native GTK4 RGB control for Omarchy: presets, per-group colors, sleep mode and a cooler panel through OpenRGB.
- **[TempHUD](https://github.com/LucasOl1337/TempHUD)** — Windows thermal overlay with a linear SuperIO fan hold, from before the move. Measured on a 9800X3D: BIOS sawtooth 74–93% fans vs 50% stable at ~69 °C under load.

#### 🏢 Production work at NexUnio

- **NexARQ** — multi-tenant SaaS for architecture firms: web, mobile, REST API, RBAC, integrations, applied AI and continuous releases.
- **NexSales** — WhatsApp attendants for clinics and stores: agent prompts, judged test sets, versioned rules and human handoff.
- **LojaSync** — React + FastAPI automation over a legacy ERP that reads Brazilian NF-e invoices and PDFs with a human review step, saving 65+ hours of manual work per month (local operational metrics). Private repository; happy to walk through it.

#### 🛠️ Stack

`Rust` · `TypeScript / React / Next.js` · `Python / FastAPI` · `C# (Unity · .NET · GTK)` · `Electron` · `PostgreSQL` · `Cloudflare` · `Vercel`
Agents: `Codex` · `Claude Code` · `Grok` · `Hermes` · multi-provider routing with 9router

10,450 contributions in the last year as of September 2026, most of them in private repositories. Studying Artificial Intelligence at FIAP (2026–2027).

#### 📫 Reach me

- 💼 **[LinkedIn](https://www.linkedin.com/in/lucasoliveiradevai)**
- 🌐 **[lucasol.cc](https://lucasol.cc)** — OL.GG, a live profile fed by my daily work logs
- Portuguese native · English advanced · Open to **remote** contract or full-time work on AI agents, developer tools and production SaaS.
