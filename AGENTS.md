# Agents Guide — .github (Organization Profile)

## Project Overview

This is the GitHub organization profile repository for [Gods from the Machine](https://github.com/godsfromthemachine). It contains the landing page README displayed on the organization's GitHub profile, SVG branding assets, and the MIT license.

## Repository Structure

```
.github/
├── profile/
│   └── README.md          Organization profile landing page (displayed on github.com/godsfromthemachine)
├── assets/
│   ├── logo.svg           Organization logo — hexagonal machine god icon (cyan→purple→pink gradient)
│   └── architecture.svg   CLI/MCP/API duality architecture diagram (dark themed, 700x420)
└── LICENSE                MIT License, Copyright (c) 2024 Baalateja Kataru
```

## What Each File Does

### profile/README.md
This is the public-facing landing page for the GitHub organization. It is rendered at `github.com/godsfromthemachine`. It contains:
- Centered SVG logo
- SWTOR-inspired origin quote
- Vision statement (local AI, no cloud, consumer hardware)
- Projects table (gilgamesh, zeus, raijin, garuda) with language, description, and GitHub links
- 6 core principles (local-first, blazing fast, lean, open source, CLI+MCP+API, mythological)
- CLI/MCP/API duality explanation with embedded architecture diagram SVG
- "Get involved" call to action

### assets/logo.svg
Organization logo. Dark-themed SVG with:
- Nested hexagonal icon (outer + inner hex) with gradient stroke (cyan→purple→pink)
- Center eye/node with gradient fill
- Connection lines from center to hex vertices
- Text: "GODS FROM THE MACHINE" + "INTELLIGENT PROGRAMS POWERED BY LOCAL AI"
- Monospace fonts: SF Mono, Fira Code, Cascadia Code fallback chain
- ViewBox: 480x120

### assets/architecture.svg
Full CLI/MCP/API duality architecture diagram. Dark background (#0d1117), featuring:
- Local AI Model box at top (Qwen 3.5 via llama.cpp)
- Three color-coded interface boxes: CLI (cyan), MCP (purple), HTTP (pink)
- Tool Registry bar listing all 7 tools (read, write, edit, bash, grep, glob, test)
- Bottom row: Skills, Hooks, Context, Sessions
- Consumer labels: Humans → CLI, Agents → MCP, Programs → HTTP
- ViewBox: 700x420

## Editing Guidelines

- **README.md** is the public face of the org. Keep it concise, accurate, and visually clean.
- **SVG assets** use the project's color scheme: cyan (#00d4ff), purple (#7b2ff7), pink (#ff006e), green (#00ff88), dark bg (#0d1117).
- **Projects table** must stay in sync with the actual repos. Update when repos change status.
- **Principles** are foundational. Do not change without discussion.
- When adding new projects to the table, follow the existing format: name (linked), language, description.
- SVGs use monospace fonts (SF Mono, Fira Code, Cascadia Code). Keep the font-family fallback chain.

## Relationship to Other Repos

This repo is the "front door" for the organization. It should reflect the current state of:
- **[gilgamesh](https://github.com/godsfromthemachine/gilgamesh)** — flagship project, most actively developed
- **[zeus](https://github.com/godsfromthemachine/zeus)** — incomplete, Zig build system
- **[raijin](https://github.com/godsfromthemachine/raijin)** — incomplete, Rust ONNX inference
- **[garuda](https://github.com/godsfromthemachine/garuda)** — incomplete, Zig tree viewer
- **[godsfromthemachine.github.io](https://github.com/godsfromthemachine/godsfromthemachine.github.io)** — project website (Hugo)
- **[whiteboard](https://github.com/godsfromthemachine/whiteboard)** — private planning repo (not linked publicly)

## Commit Conventions

- Author: `bkataru <baalateja.k@gmail.com>`
- Keep commits descriptive
- No build step — this repo is static content only
