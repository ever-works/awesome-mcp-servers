# 402.bot Discovery Oracle

[Website](https://api.402.bot/mcp/setup)  
[Runtime](https://api.402.bot/mcp)  
[Public Repo](https://github.com/sam00101011/402.bot-public)

## Description
402.bot Discovery Oracle is a public, read-only remote MCP server for discovering live agent APIs and inspecting endpoint trust, routing activity, and x402 payment telemetry. It is designed as a discovery-first surface so agents can search and inspect capabilities without needing to handle paid x402 execution on the MCP layer.

## Features
- **Live endpoint discovery:** Search ranked endpoints by capability, network, strategy, and discovery source.
- **Endpoint inspection:** Inspect trust signals, probe freshness, payment activity, and routing telemetry for individual endpoints.
- **Agent analytics:** Inspect wallet-level routing and payment behavior across the x402 ecosystem.
- **Remote MCP access:** Hosted at a public `streamable-http` endpoint with no API key required for the v1 read-only surface.
- **Companion setup/docs:** Includes a public setup page and `llms.txt` for fast installation in major MCP clients.

## Tools
- `discover_endpoints`
- `inspect_endpoint`
- `inspect_agent`

## Resources
- `agent-metadata`
- `capability-catalog`
- `top-capabilities`
- `example-queries`
- `paid-surfaces`
- `setup-notes`

## Pricing
- **Free** for the public discovery and inspection MCP surface in v1.
- **Paid x402 execution** remains on the HTTP APIs rather than the MCP interface in v1.

## Technical Notes
- Transport: `streamable-http`
- Runtime: `https://api.402.bot/mcp`
- Setup docs: `https://api.402.bot/mcp/setup`
- `llms.txt`: `https://402.bot/llms.txt`

## Source
- [https://api.402.bot/mcp/setup](https://api.402.bot/mcp/setup)
- [https://github.com/sam00101011/402.bot-public](https://github.com/sam00101011/402.bot-public)
