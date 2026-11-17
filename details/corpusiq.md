# CorpusIQ

Remote MCP server that gives an AI agent read access to the platforms a business already runs on, so it can answer questions such as last month's MRR, trending products, churned customers or ad spend by channel, with the source of each number named.

## Basic Info

- **Name:** CorpusIQ
- **Website:** https://www.corpusiq.io/
- **Docs:** https://github.com/CorpusIQ/corpusiq-docs
- **MCP Endpoint:** `https://mcp2.corpusiq.io/mcp` (Streamable HTTP)
- **MCP Registry:** `io.corpusiq/multi-source-mcp`

## Features

- 40+ connectors, including Stripe, GA4, Shopify, QuickBooks, HubSpot and Google Ads.
- Read-only, scoped access to the user's own connected accounts; data is read on demand, not copied.
- Every answer cites where each figure came from.
- Field-filtered responses, so large tables don't fill the context window.

## Setup & Configuration

- Add `https://mcp2.corpusiq.io/mcp` as a remote MCP server in an MCP-compatible client.
- Sign in with OAuth when the client connects, then connect the business accounts to query.
