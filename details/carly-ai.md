# Carly AI MCP Server

## Overview
Agent-native CLI and MCP server for [Carly](https://www.usecarly.com) — the AI scheduling assistant. Exposes booking pages, event types, calendars, slots, and bookings to any MCP-compatible client (Claude Code, Claude Desktop, Cursor, etc.) over stdio. The same command definitions drive both the CLI and the MCP server, so there is no drift between human and agent interfaces.

- **Repo:** https://github.com/shirschfield/carly-cli
- **Package:** `carly-ai` on npm
- **Language:** TypeScript / Node.js (>=18)
- **License:** MIT
- **Category:** Scheduling & Calendar MCP Servers

## Features
- 11 tools across 5 resource groups: calendars, booking-pages, event-types, slots, bookings
- Stdio-based MCP server via `carly mcp` for easy local install
- Single source of truth: each `CommandDefinition` carries Zod input schema, HTTP endpoint, field routing, and table columns — shared by CLI and MCP
- Scope-based auth (`booking_pages:read`, `booking_pages:write`, `bookings:read`), enforced server-side
- Multi-provider calendar support: Google Calendar, Microsoft Outlook/Teams, Zoom (video)
- Public availability lookup by `username + slug` for unauthenticated booking flows
- New users can sign up directly from the CLI/MCP via `carly signup` — no separate dashboard step required

## Use Cases
- Let an LLM read a user's booking pages, event types, calendars, and upcoming bookings on demand
- Programmatically create/update/disable booking pages from an agent workflow (custom questions, availability windows, duration options, buffers)
- Query availability slots by event-type ID or by public `username + slug`
- Build scheduling automations that span Google Calendar, Outlook/Teams, and Zoom from a single MCP tool surface

## Installation & Configuration

Install the CLI globally:
```
npm install -g carly-ai
```

**Claude Code:**
```
claude mcp add carly -- carly mcp
```

**Claude Desktop / Cursor** — add to `claude_desktop_config.json` or `.cursor/mcp.json`:
```json
{
  "mcpServers": {
    "carly": {
      "command": "carly",
      "args": ["mcp"],
      "env": { "CARLY_API_KEY": "carly_live_xxxx" }
    }
  }
}
```

Brand new? Run `carly signup` to create a Carly account and connect a calendar via OAuth, then `carly login` with the API key minted at `/booking-pages` → "Generate API key".

## Pricing
Free. The CLI and MCP server are MIT-licensed, and Carly itself is free to use — sign up directly from the CLI with `carly signup`.
