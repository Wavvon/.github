# Wavvon

**Built for players. Owned by no one.**

A decentralized voice + text chat platform — an open-source, self-hostable, federated alternative to Discord or TeamSpeak. Communities run their own **hubs** (a single Rust binary + PostgreSQL) that federate with each other. Identity is an Ed25519 keypair that belongs to you — no accounts, no e-mail, no company in the middle. DMs are end-to-end encrypted; hubs only ever relay ciphertext.

![A Wavvon community: unified text + voice channels, voice participants in the sidebar, live member presence](https://raw.githubusercontent.com/Wavvon/Wavvon-docs/main/assets/screenshot-channel.png)

## Get started

- **Use Wavvon** — download the [desktop app](https://github.com/Wavvon/Wavvon-clients/releases) (Windows / macOS / Linux)
- **Host a community** — run a hub in 2 minutes with Docker: [Wavvon-server](https://github.com/Wavvon/Wavvon-server)
- **Build on it** — plain HTTP + WebSocket, fully specified: [OpenAPI spec](https://github.com/Wavvon/Wavvon-docs/blob/main/openapi.yaml)

## Repositories

| Repo | Contents |
|---|---|
| [Wavvon-docs](https://github.com/Wavvon/Wavvon-docs) | Architecture wiki, roadmap, design decisions, API spec — **start here** |
| [Wavvon-server](https://github.com/Wavvon/Wavvon-server) | Hub server, federation, identity crate, fleet tooling |
| [Wavvon-clients](https://github.com/Wavvon/Wavvon-clients) | Desktop + web clients, shared packages, voice pipeline |
| [Wavvon-discovery](https://github.com/Wavvon/Wavvon-discovery) | Optional public hub directory |

Curious how it compares to Discord, Matrix, or Mumble — including its honest limitations? See the [feature comparison](https://github.com/Wavvon/Wavvon-docs/blob/main/COMPARISON.md).

Everything is [AGPL-3.0](https://github.com/Wavvon/Wavvon-docs/blob/main/LICENSE). Issues and PRs welcome in every repo.
