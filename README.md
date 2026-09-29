# Owen Wong

Automation and AI-agent engineer — I build tools that let agents operate real
software: game clients, browsers, spreadsheets and video pipelines.

Most of my work is private (client and commercial). The list below is what I can
show; happy to walk through any of it in an interview.

---

## AI agents & game automation

| Project | What it does |
|---|---|
| **sts2-mcp** | MCP server that lets an LLM actually play *Slay the Spire 2* — full combat/map/reward control, plus supporting game mods. |
| **brotato-autobattler** | Fully automated battle mod for *Brotato* (Godot 3 + GDScript): auto-shop, auto-fight, auto-level, with offline-simulated verification. |
| **stardew-ai** | AI companion for *Stardew Valley* — SMAPI C# mod + MCP bridge + Python driver. |

## Games

| Project | What it does |
|---|---|
| **guixu** | Roguelike in Phaser 3 + TypeScript. Simulation core is pure and headless-testable, so thousands of runs can be validated without a browser. |
| **abyss** / **abyss-phaser** | Action-game prototype, then a full Phaser 3 rebuild. |
| **rewind-labyrinth** | Time-rewind puzzle prototype. |

## Content & video pipelines

| Project | What it does |
|---|---|
| **yt-shorts-generator** | Long video → YouTube Shorts: automatic clipping, subtitle generation and TTS. |
| **shorts-toolkit** | Short-form production toolkit — scripting, framing and composition. |
| **holmes-shorts** | Serialised short-form production pipeline. |

## Tools & automation

| Project | What it does |
|---|---|
| **macro-recorder** | Windows mouse/keyboard macro recorder and playback — Python + PowerShell. |
| **jev-tool** | CLI for bulk fact-classification through an LLM API — high throughput at very low cost. |
| **camofox-browser** | Anti-detection browser launcher built on Camoufox. |
| **win-scripts** | Assorted Windows helpers — fast app launch, background monitors, admin setup. |
| **gpu-oc** | GPU overclock and power-limit control scripts. |
| **comfy-workflows** | ComfyUI workflow collection — image and video generation graphs. |
| **bb-pages** / **bb-builds** | Static data pages generated from crawled game data. |
| **lolclassic-scrape** | Guide scraper with an offline page archive. |

---

## How I work

- **Verify, don't assume.** Every claim comes with a before/after measurement or an
  API read-back — "should work" isn't evidence.
- **Audit before delivery.** I look for the failure mode nobody asked about, because
  the dangerous bugs are the ones that pass every checklist.
- **Test offline first.** Simulation harnesses over live poking, whenever the system
  allows it.

## Stack

Python · TypeScript / JavaScript · C# / .NET · Godot (GDScript) · Phaser · Flask ·
Next.js · Playwright / Selenium · MCP · FFmpeg · SQLite · Cloudflare Workers · Vercel
