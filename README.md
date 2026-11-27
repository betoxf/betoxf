# Hi, I'm Humberto Prado.

📍 **Seoul, South Korea** · **Product engineer** · **Native Apple software, applied AI, and operational systems**

I work at the intersection of product design, engineering, and operations—taking ideas from a rough problem to shipped software. Recent work spans macOS developer tools, Mac–PC input sharing, Apple Watch sensing, visionOS spatial interfaces, AI video workflows, 3D/IFC construction systems, and logistics platforms.

![Swift](https://img.shields.io/badge/-Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/-SwiftUI-0062D3?style=flat-square&logo=swift&logoColor=white)
![macOS](https://img.shields.io/badge/-macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

## Featured open source

### [xatlas](https://github.com/betoxf/xatlas) — the full engineering harness

An Apache-2.0 desktop app that puts all your AI coding subscriptions in one place. Claude Code, Codex, Gemini CLI and OpenCode run on your own plans, in your project's folder, and a built-in orchestrator can hand a whole job to a team of agents that plans, builds and reviews it. Built on ZCode.

- **Every agent you pay for:** pick Claude Code, Codex, Gemini CLI or OpenCode per conversation; each runs as its own CLI with its own instructions, skills and MCP servers.
- **Their work, visible:** every file read, edit and command an agent makes shows as a card with its result.
- **Jobs, not just chats (experimental):** switch a message to Orchestrate and it becomes a plan, steps built side by side in their own worktrees, each reviewed by a different agent.
- **Merging stays yours:** a job ends as reviewed branches, and the release queue shows which pull requests can ship together.
- **Projects at a glance:** every project is a stack of its conversations, most urgent in front.

**Available for macOS 14+.** No installers yet; run it from source.

```bash
git clone https://github.com/betoxf/xatlas.git
cd xatlas
pnpm bootstrap
pnpm dev:desktop:sandbox
```

[Source and setup](https://github.com/betoxf/xatlas#build-from-source) · [The orchestrator](https://github.com/betoxf/xatlas#the-orchestrator) · [Report an issue](https://github.com/betoxf/xatlas/issues)

### [UCU](https://github.com/betoxf/universal-computer-use) — AI agents that use your Mac in the background

An Apache-2.0 MCP server that lets Claude Code, opencode, and other MCP clients operate your Mac’s apps without moving your pointer or taking focus. UCU (Universal Computer Use) is an unofficial bridge to the Computer Use engine in the ChatGPT desktop app.

- **Works in the background:** agents click, type, and read other apps while you keep working.
- **Reaches apps without an accessibility tree:** agents can click by position in a background window. Some remote-desktop and canvas apps ignore background input.
- **You choose the apps:** every app is approved except the ones you deny.
- **Shows who did what:** each approval is logged with the agent and folder that caused it.
- **Light when idle:** the engine stops between uses and restarts on the next call.

**Available for macOS.** Requires the ChatGPT desktop app with Computer Use set up in Codex.

```bash
git clone https://github.com/betoxf/universal-computer-use.git
cd universal-computer-use
./ucu install
```

[Source and setup](https://github.com/betoxf/universal-computer-use#install) · [Before you use it](https://github.com/betoxf/universal-computer-use#before-you-use-it)

### [MagicInput](https://github.com/betoxf/Magicinput) — one keyboard and mouse, Mac and PC

A Rust input-sharing app, source-available and free for personal use under the PolyForm Noncommercial License 1.0.0. Push the pointer across a screen edge to move between macOS and Windows, then keep typing, clicking, and scrolling. Use either computer’s own mouse or keyboard to take control back.

- **Two-way control:** Mac → Windows and Windows → Mac, with automatic Command/Control swapping.
- **Your actual desk layout:** arrange displays by dragging them into place, including an iPad connected to the Mac through Sidecar. Auto mode also works without arranging screens.
- **Shared text clipboard:** copy on one computer and paste on the other.
- **Local connections:** automatic network discovery, code-based pairing, and encrypted input. No cloud account or telemetry.
- **Lightweight desktop integration:** menu bar and system tray controls, pointer and scroll settings, and start at login.

**Available for macOS 13+ (Apple silicon and Intel) and Windows 10/11 (64-bit).** The Mac download is signed and notarized. The Windows download is currently unsigned; setup details are in the repository.

```bash
brew install --cask betoxf/tap/magicinput
```

[Download for Mac or Windows](https://github.com/betoxf/Magicinput/releases/latest) · [Setup guide](https://github.com/betoxf/Magicinput#quick-start) · [Architecture](https://github.com/betoxf/Magicinput/blob/main/docs/ARCHITECTURE.md) · [Report an issue](https://github.com/betoxf/Magicinput/issues)

### [Usagebar](https://github.com/betoxf/Usagebar) — AI usage at a glance

A native, privacy-first macOS menu bar app for tracking Claude Code, Codex, Cursor, Kimi Code, z.ai and DeepSeek usage limits without breaking focus. Built in Swift to keep the information close and the app lightweight.

```bash
brew install --cask betoxf/tap/usagebar
```

[Downloads](https://github.com/betoxf/Usagebar/releases/latest) · [Source and setup](https://github.com/betoxf/Usagebar)

## iOS apps on the App Store

- **[Timer - Dial & Stopwatch](https://apps.apple.com/app/id6742770129)** — A countdown you set by dragging around a dial: release to start, eight dial faces, no ads or account.
- **[Skipaword - Speed Reading](https://apps.apple.com/app/id6758225981)** — RSVP speed reading that shows one to three words at a time, from 200 to 2,500 words per minute.
- **[Learn Korean - Cardio](https://apps.apple.com/app/id6748281385)** — Daily Korean practice with 1,000+ visual flashcards, pronunciation audio, Hangul writing, and spaced repetition.
- **[MeshSystem](https://apps.apple.com/app/id6795379471)** — A live 3D digital twin of a building, with comfort by floor and zone and HVAC equipment context.
- **[Foret Pilates](https://apps.apple.com/app/id6759946798)** — The class booking and schedule app for a classical Pilates studio in Chuncheon, South Korea.

## Other public work

- **[Xerebro](https://github.com/betoxf/xerebro)** — An AI-powered Mac companion for remote computer interaction through natural-language requests. The public repository documents screenshots, mouse and keyboard control, terminal commands, and web/iOS access. Distributed under a proprietary license.

## Current work

Some of my active products remain private while they are in development.

- **MeshSystem** `Private` — A 3D and IFC workspace for construction projects and building operations.
- **Postura** `Prototype` — Apple Watch and iPhone posture-sensing research with 3D feedback.
- **Omma Trucking** `Private` — A transportation and logistics platform for dispatch, fleet, drivers, payroll, and documents, on web and mobile.
- **Haulio** `Private` — A trucking operations platform.
- **Motiq** `In development` — An AI-assisted advertising and video-production workflow.

## Work with me

I'm based in Seoul, South Korea, and work with founders and teams remotely or in person in Korea.

I can help with:

- **Native Apple apps:** iPhone, iPad, Mac, Apple Watch and visionOS, from first design to App Store release.
- **AI tools and agent workflows:** developer tooling, computer use, transcription and media production.
- **Operations software:** web apps, dashboards and mobile apps that connect to how a business actually runs.

To start, email **[contact@bullfighterstudio.com](mailto:contact@bullfighterstudio.com)** with what you want to build, where it stands today, and your timeline.

[![X](https://img.shields.io/badge/-@this__is__beto-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/this_is_beto)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/betoxf)
