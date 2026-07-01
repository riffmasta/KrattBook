# KrattBook

KrattBook is a personal fork of [Docmost](https://docmost.com), tailored for a self-hosted knowledge base, notes, and documentation workflow.

## Status

This fork is being adjusted for personal use. The first customization pass removes visible Docmost product branding from the app shell, browser metadata, public-share footer, email defaults, and local Docker setup.

## Features

- Real-time collaborative pages
- Spaces and permissions
- Comments and page history
- Search
- File attachments
- Embeds
- Diagrams with Draw.io, Excalidraw, and Mermaid
- Multi-language UI inherited from upstream

## Development

Install dependencies:

```bash
pnpm install
```

Run the client and server in development:

```bash
pnpm dev
```

Build everything:

```bash
pnpm build
```

## Docker

The included Compose file builds this fork locally:

```bash
docker compose up --build
```

## Upstream And License

KrattBook is based on Docmost. The upstream open-source core is licensed under AGPL 3.0.

Enterprise directories remain subject to the upstream Docmost Enterprise license:

- `apps/server/src/ee`
- `apps/client/src/ee`
- `packages/ee`
- `packages/base-formula`
