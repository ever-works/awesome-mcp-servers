# Linq.es MCP

Official remote Streamable HTTP MCP server (`https://linq.es/mcp`) and client manifests for Linq.es Link-in-Bio profiles, `/s/` shortlinks with GA4 UTM tags, QR codes, click analytics, and inline lead capture.

## Basic Info

- **Name:** Linq.es MCP
- **Website:** https://linq.es
- **Docs:** https://linq.es/integrations/mcp
- **Source URL:** https://github.com/giulianobr/linqes-mcp
- **MCP Endpoint:** `https://linq.es/mcp` (Streamable HTTP, JSON-RPC 2.0)
- **MCP Registry:** `io.github.giulianobr/linqes-mcp`
- **Glama Connector:** https://glama.ai/mcp/connectors/io.github.giulianobr/linqes-mcp
- **License:** MIT

## Features

- Manage Link-in-Bio profiles and link cards (`list_profiles`, `list_profile_links`, `add_profile_link`, `update_profile_link`, `delete_profile_link`, `import_bio_links`).
- Create and inspect `/s/:code` shortlinks with custom vanity slugs, iOS/Android routing, and GA4 UTM tags (`list_shortlinks`, `create_shortlink`).
- Retrieve 7-to-90-day profile views, link clicks, CTR, top referrers, countries, devices, and daily time series (`get_profile_analytics`).
- List captured contacts from Lead Magnet forms (`list_leads`).

## Setup & Configuration

- Generate a personal API key (`lnq_live_...`) in Linq.es Account Settings.
- Connect any MCP-compatible client directly to `https://linq.es/mcp` with `Authorization: Bearer ${LINQES_API_KEY}` (no local runtime required).
