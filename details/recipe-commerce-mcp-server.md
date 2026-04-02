## Overview

Recipe Commerce MCP is a production-ready MCP server that extracts affiliate-ready ingredient and product entities from recipe content. It transforms recipe pages, markdown, or structured recipe data into actionable commerce intelligence for AI agents to use for affiliate marketing, kitchen product discovery, and content monetization.

## Features

- **Ingredient & Product Extraction**: Identifies ingredients, cookware, appliances, and specialty products
- **Brand Detection**: Recognizes brand names even when recipes use generic terms
- **Substitute Suggestions**: Identifies mentioned ingredient substitutes with affiliate opportunities
- **Confidence Scoring**: Rates extraction confidence per entity (0.0–1.0)
- **Category Classification**: Groups products by type (produce, pantry, equipment, specialty)
- **100% F1 Accuracy**: Validated against real recipe content with ground truth fixtures
- **x402 Micropayments**: Pay-per-call via USDC/Stripe — $0.01/call

## Remote Endpoint

Available as a hosted Cloudflare Workers endpoint — no installation required:

```
https://recipe-commerce-mcp.sincetoday.workers.dev/mcp
```

Free tier: 200 calls/day, no API key required.

## Tools

- `extract_recipe_products` — Main extraction tool for recipe content
- `analyze_recipe_ingredients` — Deep ingredient analysis with brand and substitute detection
- `generate_recipe_products_section` — Format extracted products as shoppable recipe section
- `get_extraction_health` — Check service status and rate limit information

## Use Cases

- Food blog monetization: automatically identify affiliate opportunities in recipe archives
- Kitchen product discovery: extract cookware and appliance recommendations from recipes
- Ingredient research: understand what specialty ingredients recipes actually need
- Shopping list automation: generate shoppable ingredient lists from recipe content

## Pricing

- **Free tier**: 200 calls/day per agent, no API key required
- **Paid**: $0.01/call via x402 micropayments (USDC on Base or Stripe)
- **API key**: Available for high-volume use cases
