## Overview

Podcast Commerce MCP is a production-ready MCP server that extracts affiliate-ready product entities from podcast transcripts. It transforms unstructured audio content descriptions into structured commerce data that AI agents can use for affiliate marketing, product research, and content monetization.

## Features

- **Product Entity Extraction**: Identifies product names, brands, categories, and prices from podcast transcripts
- **Recommendation Strength Scoring**: Rates how strongly a host recommends each product (0.0–1.0)
- **Speaker Attribution**: Associates product mentions with specific speakers
- **Sponsor Analysis**: Distinguishes between organic mentions and paid sponsorships
- **Cross-Episode Analysis**: Compare products across multiple podcast episodes
- **100% F1 Accuracy**: Validated against real podcast content with ground truth fixtures
- **x402 Micropayments**: Pay-per-call via USDC/Stripe — $0.01/call

## Remote Endpoint

Available as a hosted Cloudflare Workers endpoint — no installation required:

```
https://podcast-commerce-mcp.sincetoday.workers.dev/mcp
```

Free tier: 200 calls/day, no API key required.

## Tools

- `extract_podcast_products` — Main extraction tool for podcast transcripts
- `analyze_episode_sponsors` — Identify and score sponsorships vs organic mentions
- `compare_products_across_shows` — Aggregate products across multiple episodes
- `generate_show_notes_section` — Format extracted products as shoppable show notes
- `get_extraction_health` — Check service status and rate limit information

## Use Cases

- Podcast monetization: identify affiliate opportunities in existing content
- Market research: track product trends across podcast categories
- Content intelligence: understand what products your audience engages with
- Affiliate page generation: auto-generate product pages from podcast content

## Pricing

- **Free tier**: 200 calls/day per agent, no API key required
- **Paid**: $0.01/call via x402 micropayments (USDC on Base or Stripe)
- **API key**: Available for high-volume use cases
