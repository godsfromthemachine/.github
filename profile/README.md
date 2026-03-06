<p align="center">
  <img src="assets/logo.svg" alt="Gods from the Machine" width="480"/>
</p>

<p align="center">
  <em>Inspired by the <a href="https://starwars.fandom.com/wiki/Machine_Gods_crisis">Gods from the Machine</a> raid in Star Wars: The Old Republic — a pantheon of ancient, sentient super-weapons worshiped as deities on the mechanical Dyson sphere planet Iokath.</em>
</p>

## Vision

We build autonomous, AI-powered software — "gods in the machine" — that operate entirely on local, private, offline AI models. No cloud dependencies. No API keys to external services. Just raw local inference powering intelligent programs.

Every project is designed to run on consumer hardware using small, capable models (Qwen 3.5 family: 0.8B, 2B, 4B, 9B) served via llama.cpp.

## Projects

| Project | Language | Description |
|---------|----------|-------------|
| **[gilgamesh](https://github.com/godsfromthemachine/gilgamesh)** | Go | TDD-driven local AI coding agent. CLI + MCP + HTTP API. Tool-calling, streaming SSE, skills, hooks, session logging. Includes Go [benchmark suite](https://github.com/godsfromthemachine/gilgamesh/blob/main/TRIALS.md) for model trialing. |
| **[zeus](https://github.com/godsfromthemachine/zeus)** | Zig | Zig-as-a-build-system for llama.cpp-powered local GGUF inference. *(incomplete)* |
| **[raijin](https://github.com/godsfromthemachine/raijin)** | Rust | ONNX CPU inference engine. *(incomplete)* |
| **[garuda](https://github.com/godsfromthemachine/garuda)** | Zig | Directory tree viewer. *(incomplete)* |
| **[godsfromthemachine.github.io](https://github.com/godsfromthemachine/godsfromthemachine.github.io)** | Hugo | Official project website — architecture, roadmap, and documentation. |

## Principles

- **Local-first**: All intelligence comes from free, local, private AI models
- **Blazing fast**: Built in Go, Rust, Zig, and other high-performance languages
- **Lean**: Minimal token overhead for CPU inference — first response in seconds, not minutes
- **Open source**: MIT/GNU licensed — free to use, learn from, and contribute to
- **CLI + MCP + API**: Every god has CLI, MCP, and HTTP/API interfaces
- **Mythological**: Projects named after gods and legends — each one a specialized autonomous entity

## The CLI / MCP / API Duality

Every god exposes the same capabilities through three interfaces — because every MCP tool functions just as well as a CLI command given to an agent via a shell, and just as well as an HTTP endpoint called by another program. We build all three so gods can interface with human users, other agents, external programs, and each other.

<p align="center">
  <img src="assets/architecture.svg" alt="CLI / MCP / API Architecture" width="700"/>
</p>

## Get involved

All projects are open source. Browse the repos, open issues, submit PRs. We're building the future of autonomous local AI software.

**[godsfromthemachine.github.io](https://godsfromthemachine.github.io)** — Visit the website for architecture docs, roadmap, and more.
