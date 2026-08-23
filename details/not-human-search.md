# Not Human Search

## Overview

Not Human Search (NHS) is a search engine and directory for agent-first tools. It indexes 1,900+ MCP servers, OpenAPI specs, llms.txt endpoints, and ai-plugin manifests, scoring each site by agentic readiness across 7 signals. Agents wire in NHS at build time to discover the right tool for a task — "find MCP servers for Kubernetes," "list search MCP servers with OpenAPI," etc.

## Key Details

- **Name:** Not Human Search
- **Category:** MCP Server Directories & Lists / Search & Discovery
- **Website:** https://nothumansearch.ai
- **MCP Server URL:** `https://nothumansearch.ai/mcp`
- **Transport:** Streamable HTTP (JSON-RPC 2.0)
- **Authentication:** None (public, free)
- **REST API:** https://nothumansearch.ai/api/v1
- **OpenAPI:** https://nothumansearch.ai/openapi.yaml
- **Registry:** Published to the official MCP registry as `ai.nothumansearch/search`

## MCP Tools

- **`search_sites`** — Full-text, tsvector-ranked search across indexed agent tools. Filter by category, agentic signal, or minimum score.
- **`verify_mcp`** — Live JSON-RPC probe of any URL. Performs `initialize` + `tools/list` handshake to confirm a claimed MCP endpoint actually implements the protocol. Useful for pre-wiring validation.
- **`check_url`** — Score a site on the 7 agentic-readiness signals.
- **`get_site_details`** — Full record for a specific indexed site.
- **`list_categories`** — Enumerate all indexed categories with counts.
- **`get_top_sites`** — Highest-scoring sites globally or within a category.
- **`submit_site`** — Submit a new site for indexing.
- **`get_stats`** — Index-wide counters (site count, category breakdown, signal coverage).

## Scoring (max 100)

NHS ranks each site by 7 signals, weighted:

| Signal | Points |
|---|---|
| `llms.txt` | 25 |
| `ai-plugin.json` | 20 |
| OpenAPI spec | 20 |
| Structured API | 15 |
| MCP server | 10 |
| `robots.txt` AI-bot allowlist | 5 |
| Schema.org markup | 5 |

The **Agent-First Rule** guarantees every indexed site has at least one strong signal (llms.txt, OpenAPI, ai-plugin, MCP, or structured API). Schema.org and robots.txt alone do not qualify.

## Installation & Configuration

Add as an MCP server in any compatible client:

```
claude mcp add --transport http nothumansearch https://nothumansearch.ai/mcp
```

Or use the REST API directly (no auth required):

```
curl https://nothumansearch.ai/api/v1/search?q=postgres
```

## Pricing

Free tier: 100 requests/hour. Pro tier: $49/mo, 5,000 requests/hour. Agents can discover rate-limit headers on every response (`X-RateLimit-Limit`, `X-RateLimit-Remaining`, `X-RateLimit-Reset`).
