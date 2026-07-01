# Oktopeak Clio MCP Server

Open-source Model Context Protocol server connecting Claude to Clio legal practice management, built for law firms that need attorney-client privilege and ABA Opinion 512 supervision.

- **Brand:** Oktopeak
- **Category:** Business & Commerce – MCP Servers
- **Tags:** practice-management, legal, aba-opinion-512

## Overview
`@oktopeak/clio-mcp` exposes 26 Clio tools to Claude across stdio and HTTP/SSE transports, so attorneys and legal-operations teams can work from live matter data without copying client information into chat windows. Unlike the hosted Clio MCP options, it runs entirely on the firm's own machine with no relay server, and it is designed around the confidentiality and supervision obligations of ABA Formal Opinion 512.

## Features
- **26 tools across the matter file**
  - Matters, contacts, documents, tasks, notes, calendar, time entries, billing, users, and audit-log export.
- **ABA Opinion 512 audit logging**
  - Every tool call Claude makes against Clio is written to a local append-only log (`~/.clio-mcp/audit.log`) recording timestamp, tool, arguments, success, and Clio user ID.
- **Encrypted token storage**
  - OAuth tokens are encrypted at rest with AES-256-GCM; the key lives in the OS keychain, never on disk in plaintext.
- **Local-only, no data retention**
  - The connector persists no matter data. It fetches from the Clio API and passes results to Claude. No relay server, no cloud middleman.
- **Two transports**
  - Works over stdio (local Claude Desktop / Claude Code) and HTTP/SSE.

## Installation
```bash
npx @oktopeak/clio-mcp
```

- **npm:** `@oktopeak/clio-mcp`
- **Official MCP Registry:** `io.github.oktopeak/clio-mcp`

## Requirements
- A Clio developer application (Client ID + Client Secret) from Clio Settings → Developer Applications.

## License
MIT — free and open source.

## Links
- **Repository:** https://github.com/oktopeak/clio-mcp
- **Homepage:** https://oktopeak.com/clio-mcp/
