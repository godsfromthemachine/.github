# Gods from the Machine

Intelligent programs powered by local AI. Autonomous software that builds, runs, and improves itself.

Inspired by the [Gods from the Machine](https://starwars.fandom.com/wiki/Machine_Gods_crisis) raid in Star Wars: The Old Republic — a pantheon of ancient, sentient super-weapons worshiped as deities on the mechanical Dyson sphere planet Iokath.

## Vision

We build autonomous, AI-powered software — "gods in the machine" — that operate entirely on local, private, offline AI models. No cloud dependencies. No API keys to external services. Just raw local inference powering intelligent programs.

Every project is designed to run on consumer hardware using small, capable models (Qwen 3.5 family: 0.8B, 2B, 4B, 9B) served via llama.cpp.

## Projects

| Project | Language | Description |
|---------|----------|-------------|
| **[gilgamesh](https://github.com/godsfromthemachine/gilgamesh)** | Go | TDD-driven local AI coding agent. CLI + MCP + HTTP API interfaces. Tool-calling, streaming SSE, skills, hooks, session logging. |
| **[zeus](https://github.com/godsfromthemachine/zeus)** | Zig | Zig-as-a-build-system for llama.cpp-powered local GGUF inference. |
| **[raijin](https://github.com/godsfromthemachine/raijin)** | Rust | Lightning-fast CPU inference via ONNX runtime. |
| **[garuda](https://github.com/godsfromthemachine/garuda)** | Zig | Directory tree viewer replicating PowerShell's tree command. |

## Principles

- **Local-first**: All intelligence comes from free, local, private AI models
- **Blazing fast**: Built in Go, Rust, Zig, and other high-performance languages
- **Lean**: Minimal token overhead for CPU inference — first response in seconds, not minutes
- **Open source**: MIT/GNU licensed — free to use, learn from, and contribute to
- **CLI + MCP + API**: Every god has CLI, MCP, and HTTP/API interfaces
- **Mythological**: Projects named after gods and legends — each one a specialized autonomous entity

## The CLI / MCP / API Duality

Every god exposes the same capabilities through three interfaces — because every MCP tool functions just as well as a CLI command given to an agent via a shell, and just as well as an HTTP endpoint called by another program. We build all three so gods can interface with human users, other agents, external programs, and each other.

```
                    ┌──────────────────────┐
                    │   Local AI Model     │
                    │  (Qwen 3.5 / GGUF)  │
                    └──────────┬───────────┘
                               │
                    OpenAI-compatible API
                               │
            ┌──────────────────┼──────────────────┐
            │                  │                  │
     ┌──────┴──────┐  ┌───────┴───────┐  ┌───────┴───────┐
     │  CLI REPL   │  │  MCP Server   │  │  HTTP API     │
     │  (terminal) │  │  (stdio/rpc)  │  │  (REST/SSE)   │
     └──────┬──────┘  └───────┬───────┘  └───────┬───────┘
            │                  │                  │
            └──────────────────┼──────────────────┘
                               │
                    ┌──────────┴──────────┐
                    │  Tools / Skills /   │
                    │  Hooks / Context    │
                    └─────────────────────┘
```

## Get involved

All projects are open source. Browse the repos, open issues, submit PRs. We're building the future of autonomous local AI software.
