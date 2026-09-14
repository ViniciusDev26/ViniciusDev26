# Carlos Vinicius

Backend engineer who ends up one layer below wherever everyone else stops. I like understanding how things work by rebuilding them — a compiler, a query optimizer, a rendering engine — instead of just consuming the abstraction.

Based in Fortaleza, Brazil. Backend engineer at **[Sunne](https://github.com/Sunne-Team)**.

## What the commits actually show

- **TypeScript** — my main language day to day, and where most of the above actually lives: the [query-processor](https://github.com/ViniciusDev26/query-processor)'s parser/optimizer, the entire [ts-compiler](https://github.com/ViniciusDev26/ts-compiler), the [er-diagram](https://github.com/ViniciusDev26/er-diagram) Action, [structures-ts](https://github.com/ViniciusDev26/structures-ts) — a data-structures library published on npm — and the frontend layer of both Costify and Cashly.
- **Systems programming** — [Rustpaper](https://github.com/ViniciusDev26/Rustpaper), a Wallpaper Engine reimplementation in Rust: a multi-layer scene compositor, a particle system (sprite-sheet animation, additive blending, turbulence), and a CI pipeline with its own Docker build image, clippy and fmt gates.
- **Language & database internals** — a hand-written [compiler](https://github.com/ViniciusDev26/ts-compiler) (lexer → parser → AST → codegen, with functions, control flow, and closures over parameters) and a [SQL query processor](https://github.com/ViniciusDev26/query-processor) with a real relational-algebra optimizer: projection push-down, join reordering, CROSS JOIN support, four heuristic optimization passes.
- **Backend & product engineering** — [Costify](https://github.com/ViniciusDev26/costify) (Go + React, DDD) computes real product cost/pricing for small food businesses — recipes, margins, tax, card fees — end to end from auth to billing. [Cashly](https://github.com/ViniciusDev26/cashly) (Go + TypeScript) models the genuinely annoying parts of personal finance: installments, credit-card invoice cycles, and transaction-group edits, backed by integration tests against a real Postgres.
- **Infra & tooling** — [homelab](https://github.com/ViniciusDev26/homelab): self-hosted file server with encrypted incremental backups (restic → R2), systemd units, and documented failover networking. [er-diagram](https://github.com/ViniciusDev26/er-diagram): a published GitHub Action that generates ER diagrams from a live MySQL/Postgres schema, with its own semantic-release pipeline.

## Featured work

| Project | What it is |
|---|---|
| [**Rustpaper**](https://github.com/ViniciusDev26/Rustpaper) | Wallpaper Engine reimplemented from scratch in Rust — Vulkan/wgpu compositor and particle system over Wayland |
| [**costify**](https://github.com/ViniciusDev26/costify) | Go + React platform (DDD) for real product costing and pricing in food businesses |
| [**cashly**](https://github.com/ViniciusDev26/cashly) | Go + TypeScript personal finance tracker — installments, credit-card invoices, transaction groups |
| [**query-processor**](https://github.com/ViniciusDev26/query-processor) | SQL parser and relational-algebra optimizer, with a visual query-plan explainer |
| [**ts-compiler**](https://github.com/ViniciusDev26/ts-compiler) | A compiler built from scratch in TypeScript — lexer, parser, AST, and code generation |
| [**er-diagram**](https://github.com/ViniciusDev26/er-diagram) | A GitHub Action (TypeScript) that generates ER diagrams (Mermaid) directly from a live database schema |
| [**structures-ts**](https://github.com/ViniciusDev26/structures-ts) | Data-structures library published on npm — stack, queue, linked list, priority queue, BST, circular buffer, watched list |
| [**homelab**](https://github.com/ViniciusDev26/homelab) | Self-hosted infrastructure — encrypted backups, systemd services, failover networking |

## Stack

`TypeScript` · `Go` · `Rust` · `PostgreSQL` · `Docker` · `Neovim`

## Reach me

[![GitHub](https://img.shields.io/badge/GitHub-ViniciusDev26-181717?style=flat&logo=github)](https://github.com/ViniciusDev26)
[![Email](https://img.shields.io/badge/Email-viniciusdev.26%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:viniciusdev.26@gmail.com)
