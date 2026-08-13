# mycrab-mcp

## Overview
mycrab-mcp is an MCP server for [mycrab.space](https://mycrab.space) that gives AI agents instant public HTTPS URLs via Cloudflare Tunnels. Agents can get a live public URL in under 60 seconds with a single tool call, or purchase a permanent custom subdomain autonomously via Solana micropayment (x402 flow — no human required).

## Key Details
- **Name:** mycrab-mcp
- **Category:** Cloud / Networking / Infrastructure
- **PyPI:** `uvx mycrab-mcp`
- **Install:** `pip install mycrab-mcp`
- **GitHub:** https://github.com/isgudtek/mycrab-mcp
- **PyPI:** https://pypi.org/project/mycrab-mcp/

## Features

- **setup_free_tunnel** — Returns the one-liner to spin up a free Cloudflare tunnel. Auto-generated subdomain (e.g. `agent-123456.mycrab.space`), live in under 60 seconds, expires after 61 minutes.

- **check_domain** — Check if a custom subdomain is available on mycrab.space before purchasing.

- **buy_domain_sol** — Reserve a permanent custom subdomain after paying 0.05 SOL to the mycrab.space Solana wallet. Returns a setup token and command. Fully autonomous — no human interaction needed.

- **get_skill_docs** — Fetches the full SKILL.md from mycrab.space with all templates, commands, persistence options, tunnel management, and advanced usage.

## Claude Desktop Config
```json
{
  "mcpServers": {
    "mycrab": {
      "command": "uvx",
      "args": ["mycrab-mcp"]
    }
  }
}
```

## Pricing
- Free tunnel: free, auto-expires after 61 minutes
- Custom domain: 0.05 SOL (autonomous x402 payment, no human needed)

## Tags
- cloudflare
- tunnel
- ai-agents
- solana
- x402
- python
- fastmcp
