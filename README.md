# Carlos Vinicius

Backend engineer who ends up one layer below wherever everyone else stops. I like understanding how things work by rebuilding them — a compiler, a query optimizer, a rendering engine — instead of just consuming the abstraction.

Based in Fortaleza, Brazil. Senior Backend Engineer at **[Sunne](https://github.com/Sunne-Team)**, where I work on the billing and payments microservices of a renewable-energy company — invoicing, boleto, Pix, bank transfers and automated utility-bill payments — on Node.js/TypeScript, PostgreSQL, MySQL, AWS SQS/S3 and GCP Pub/Sub, with TDD and Clean Architecture as the default.

## Sugomi

I own and maintain **[sugomi-dev](https://github.com/sugomi-dev)**, the home of my developer tools: fast, focused and mostly open source.

| Project | What it is |
|---|---|
| [**prunr**](https://github.com/sugomi-dev/prunr) | A dead-code detector for Node.js in Rust: unused files, exports and dependencies, with CommonJS as a first-class citizen. Ships as a CLI on npm and as a GitHub Action |
| [**Rustpaper**](https://github.com/sugomi-dev/Rustpaper) | Wallpaper Engine wallpapers on Linux and Wayland, on any layer-shell compositor |

## What the commits actually show

- **TypeScript** — my main language day to day, and where most of the above actually lives: the [query-processor](https://github.com/ViniciusDev26/query-processor)'s parser/optimizer, the entire [ts-compiler](https://github.com/ViniciusDev26/ts-compiler), the [er-diagram](https://github.com/ViniciusDev26/er-diagram) Action and [whatstalks](https://github.com/ViniciusDev26/whatstalks), a CLI that speaks WhatsApp's WebSocket protocol directly.
- **Systems programming** — [Rustpaper](https://github.com/sugomi-dev/Rustpaper), a Wallpaper Engine reimplementation in Rust: a multi-layer scene compositor, a particle system (sprite-sheet animation, additive blending, turbulence), and a CI pipeline with its own Docker build image, clippy and fmt gates.
- **Language & database internals** — a hand-written [compiler](https://github.com/ViniciusDev26/ts-compiler) (lexer → parser → AST → codegen, with functions, control flow, and closures over parameters) and a [SQL query processor](https://github.com/ViniciusDev26/query-processor) with a real relational-algebra optimizer: projection push-down, join reordering, CROSS JOIN support, four heuristic optimization passes.
- **Backend & tooling** — production Go backends (clean architecture, DDD, Postgres) in private client work, and [er-diagram](https://github.com/ViniciusDev26/er-diagram): a published GitHub Action that generates ER diagrams from a live MySQL/Postgres schema, with its own semantic-release pipeline.

## Featured work

| Project | What it is |
|---|---|
| [**query-processor**](https://github.com/ViniciusDev26/query-processor) | SQL parser and relational-algebra optimizer, with a visual query-plan explainer |
| [**ts-compiler**](https://github.com/ViniciusDev26/ts-compiler) | A compiler built from scratch in TypeScript — lexer, parser, AST, and code generation |
| [**er-diagram**](https://github.com/ViniciusDev26/er-diagram) | A GitHub Action (TypeScript) that generates ER diagrams (Mermaid) directly from a live database schema |
| [**whatstalks**](https://github.com/ViniciusDev26/whatstalks) | CLI, published on npm, that talks to WhatsApp's WebSocket directly (via Baileys, no browser) to send a script line by line |

## Stack

`TypeScript` · `Node.js` · `Go` · `Rust` · `PostgreSQL` · `Docker` · `Neovim`

## Reach me

[![GitHub](https://img.shields.io/badge/GitHub-ViniciusDev26-181717?style=flat&logo=github)](https://github.com/ViniciusDev26)
[![Email](https://img.shields.io/badge/Email-viniciusdev.26%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:viniciusdev.26@gmail.com)
