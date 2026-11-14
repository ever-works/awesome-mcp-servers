## Overview

[datawebot](https://www.datawebot.com) is a hosted MCP server that gives AI agents ecommerce product data. It searches products across online shops worldwide, lists every seller's price for one product with direct shop links, and runs extraction Jobs on Amazon search and product pages (10 countries) and 1,100+ Shopify stores.

## Connection and access

- Endpoint: `https://mcp.datawebot.com/mcp`
- Transport: Streamable HTTP (remote, nothing to install)
- Authentication: OAuth 2.1 per the MCP spec (email sign-in); an `Authorization: Bearer <API key>` header is also accepted.
- Access: sign-in is free; usage is paid from 200 free trial credits.
- MCP Registry: `com.datawebot/datawebot`
- Docs: [datawebot.com/docs/agents](https://www.datawebot.com/docs/agents)
- Connection kit (MIT): [datawebot/datawebot-mcp](https://github.com/datawebot/datawebot-mcp)

## Tools

- `discover`
- `search_products`
- `get_product_offers`
- `list_job_blueprints`
- `submit_job`
- `get_job`
- `get_results`
- `run_tool`
