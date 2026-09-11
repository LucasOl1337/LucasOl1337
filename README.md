### Hi, I'm Lucas 👋

**AI engineer. I build products and tools with AI agents.** São Paulo, Brazil.

I am not a traditional developer and I don't try to be one. My job is to define the problem, write the brief, split the work, run builders and reviewers as separate agents (Codex, Claude Code, Grok, Hermes) and own the product decisions, the integration, the tests and the final result. Every project below was built this way. Most of my public tooling exists so I can run more of that at once.

#### 📈 Volume, from my own logs

- **11,099 GitHub contributions** in the last year (as of September 11, 2026), most of them in private repositories. Current streak: 82 days.
- **~3.8 billion tokens** processed between September 4 and 11, 2026, in Codex and Claude Code alone: about 2.77B in Codex and 1.02B in Claude Code, 15M of them generated output. Grok CLI, Cursor and Pi run on top of that and are not counted here.
- **3,800+ agent conversations and 244k messages** in the last 33 days, read by DailyWork from the local session files of every harness I use.

These are activity numbers, not quality numbers. The quality is in the releases below.

#### 🧰 Tools for working with AI agents

- **[RamDog](https://github.com/LucasOl1337/RamDog)** — process manager for Windows, Linux and macOS, in Rust. Groups processes by the app that started them, shows origin and categories, tree kill and locks. [v0.9.0](https://github.com/LucasOl1337/RamDog/releases/tag/v0.9.0) ships packages for all three systems.
- **[KamuiT](https://github.com/LucasOl1337/kamuit)** — native terminal workspace for AI agents (Grok, Claude, Codex, Pi): Windows Terminal core on Windows, GTK4 + VTE on Linux, with CLI, IPC and MCP so agents can open their own tabs.
- **[Estúdio](https://github.com/LucasOl1337/estudio)** — Rust window over an image-generation pipeline: references, use cases, Codex or Grok batches, live progress and previous results in one place.
- **DailyWork** (private) — Electron app that reads every agent session on this machine, writes my daily summary, runs an editorial queue with evidence checks and produces the numbers above. Its public face is [lucas-ol.com](https://lucas-ol.com).
- **[The Last Arrow](https://github.com/LucasOl1337/The-Last-Arrow)** — Unity/C# arena where external LLM agents receive game state and act through a Python broker, with persistent bot profiles and observability overlays.
- **[ChessCam](https://github.com/LucasOl1337/ChessCam)** — real-time multiplayer chess: WebSocket netcode, server-validated moves, reconnect handling and match review. A model timeout pauses the match instead of inventing a move.

#### 🐧 Linux / Omarchy

I moved my daily setup to Omarchy (Arch + Hyprland) in September 2026 and started shipping what I was missing:

- **[Sussurro](https://github.com/LucasOl1337/sussurro)** — local dictation for Windows and Linux: Silero VAD + faster-whisper on CUDA, text typed or pasted where the cursor is. No audio leaves the machine. [v0.3.0](https://github.com/LucasOl1337/sussurro/releases/tag/v0.3.0) · [site](https://lucasol1337.github.io/sussurro/)
- **[Ponte](https://github.com/LucasOl1337/ponte)** — touch controls and live monitor views for an Omarchy desktop from an Android phone, over Tailscale. Experimental alpha, verified on a real device. [project page](https://lucasol1337.github.io/ponte/)
- **[Magma](https://github.com/LucasOl1337/magma-lights)** — native GTK4 RGB control for Omarchy: presets, per-group colors, sleep mode and a cooler panel through OpenRGB.
- **[TempHUD](https://github.com/LucasOl1337/TempHUD)** — Windows thermal overlay with a linear SuperIO fan hold, from before the move. Measured on a 9800X3D: BIOS sawtooth 74–93% fans vs 50% stable at ~69 °C under load.

#### 🏢 Production work at NexUnio

- **NexSales** — AI attendants on WhatsApp for clinics and stores: agent prompts, judged test sets (Claude Fable vs GPT on the same conversations), versioned rules and human handoff. Real appointments booked in production.
- **NexARQ** — multi-tenant SaaS for architecture firms: web, mobile, REST API, RBAC, integrations, applied AI and continuous releases.
- **SFR Resgate Digital** — offline-first React Native/Expo app for pre-hospital rescue teams: clinical forms, burn map, local persistence and sync recovery, updated over the air on a real fleet.
- **LojaSync** — React + FastAPI automation over a legacy ERP that reads Brazilian NF-e invoices and PDFs with a human review step, saving 65+ hours of manual work per month (local operational metrics). Private repository; happy to walk through it.

#### 🛠️ Stack

`Rust` · `TypeScript / React / Next.js` · `Python / FastAPI` · `C# (Unity · .NET · GTK)` · `Electron` · `PostgreSQL` · `Cloudflare` · `Vercel`
Agents: `Codex` · `Claude Code` · `Grok` · `Hermes` · multi-provider routing with 9router

Studying Artificial Intelligence at FIAP (2026–2027).

#### 📫 Reach me

- 💼 **[LinkedIn](https://www.linkedin.com/in/lucasoliveiradevai)**
- 🌐 **[lucas-ol.com](https://lucas-ol.com)** — live profile fed by my daily work logs
- Portuguese native · English advanced · Open to **remote** contract or full-time work as an AI engineer: agents in production, developer tools and SaaS.
