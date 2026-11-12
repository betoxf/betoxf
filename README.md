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

## Other public work

- **[Xerebro](https://github.com/betoxf/xerebro)** — An AI-powered Mac companion for remote computer interaction through natural-language requests. The public repository documents screenshots, mouse and keyboard control, terminal commands, and web/iOS access. Distributed under a proprietary license.

## Current work

Some of my active products remain private while they are in development.

- **xatlas** `Private` — A native macOS command environment for projects, terminals, Git, MCPs, skills, and automations.
- **MeshSystem** `Private` — A 3D and IFC workspace for construction projects and building operations.
- **Postura** `Prototype` — Apple Watch and iPhone posture-sensing research with 3D feedback.
- **Omma Trucking** `Private` — A transportation and logistics platform for dispatch, fleet, drivers, payroll, and documents, on web and mobile.
- **Haulio** `Private` — A trucking operations platform.
- **Motiq** `In development` — An AI-assisted advertising and video-production workflow.

## Engineering focus

- **Native desktop software:** Swift, SwiftUI, macOS integration, and small utilities that fit everyday workflows.
- **Systems and device interaction:** Rust, cross-platform input, networking, and desktop services.
- **Applied AI:** tools for developer workflows, computer interaction, transcription, and media production.
- **Web and operations:** TypeScript, React, Cloudflare, and software that connects product interfaces with real business processes.

## How I build

- Start with a real problem and reduce it to the smallest useful product.
- Prefer native experiences when platform integration and performance matter.
- Keep privacy-sensitive workflows local-first whenever possible.
- Own the path from product design and implementation through testing and release.

## Connect

I'm interested in thoughtful collaborations around native Apple software, practical AI tools, and applied product engineering.

[![X](https://img.shields.io/badge/-@this__is__beto-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/this_is_beto)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/betoxf)
