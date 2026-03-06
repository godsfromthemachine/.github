# CLAUDE.md — .github (Organization Profile)

## What is this?

GitHub organization profile repo for [Gods from the Machine](https://github.com/godsfromthemachine). Contains the landing page README, SVG branding assets, and license. No code — static content only.

## Files

```
profile/README.md       Org landing page (rendered at github.com/godsfromthemachine)
assets/logo.svg         Org logo (hexagonal icon, cyan→purple→pink gradient, 480x120)
assets/architecture.svg CLI/MCP/API duality diagram (dark bg, 700x420)
LICENSE                 MIT, Baalateja Kataru
```

## Critical Rules

- **profile/README.md is the public face.** Keep it accurate, concise, and in sync with actual repo status.
- **Color scheme**: cyan (#00d4ff), purple (#7b2ff7), pink (#ff006e), green (#00ff88), dark bg (#0d1117).
- **SVG fonts**: monospace chain — SF Mono, Fira Code, Cascadia Code.
- **Projects table** lists all public repos with status. Update when repos change.
- **Do not link to whiteboard** — it is a private repo.
- **Author**: `bkataru <baalateja.k@gmail.com>`.

## Context

Gods from the Machine builds autonomous, AI-powered software that runs entirely on local models. Every project ("god") is named after a mythological deity and exposes CLI, MCP, and HTTP interfaces over a shared tool registry. Key principles: local-first, zero external deps, lean token budget, open source (MIT), high-performance languages (Go, Rust, Zig).
