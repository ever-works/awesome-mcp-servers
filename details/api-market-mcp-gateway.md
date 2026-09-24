# API.market MCP Gateway

API.market MCP Gateway is a provider-operated hosted Model Context Protocol service for discovering and calling APIs from AI agents. Its catalog advertises 580+ APIs for image and video generation, search, web data, maps and other workflows.

## Connection

- **MCP endpoint:** https://api.market/api/mcp/gateway
- **Transport:** Streamable HTTP
- **Authentication:** OAuth recommended; API-key authentication also supported
- **Setup documentation:** https://api.market/mcp
- An API.market account is required.

The setup page is not an MCP endpoint. Use the gateway URL in client connection fields.

## Capabilities

Live version 3.0.0 exposes five gateway tools:

- `search_apis`: find APIs in the catalog
- `get_api_tools`: retrieve API operation schemas
- `call_api`: execute an API operation
- `check_usage`: inspect usage
- `manage_subscription`: manage API subscriptions

The server also exposes two resources and two prompts. The catalog size is not the number of directly exposed MCP tools.

## Pricing

Free tiers and paid plans vary by API. Check each API's pricing and subscription requirements before invoking paid operations.

## Implementation and verification

This is a proprietary hosted service. The public [integration repository](https://github.com/Noveum/api-market-agent-integrations) contains client configuration and publishing metadata, not the hosted implementation. It is distinct from the older local [API Market Server](api-market-server.md).

OAuth discovery, dynamic client registration, authorization-code exchange with S256 PKCE, authenticated initialize and capability listing were checked on 2026-09-24. This does not claim every catalog API or client integration was tested.

## Registry

[Official MCP Registry record](https://registry.modelcontextprotocol.io/v0.1/servers/io.github.Noveum%2Fapi-market-gateway/versions/3.0.0)

## Tags

api-integration, oauth, remote, ai-agents
