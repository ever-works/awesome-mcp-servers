## Overview

Newsletter Commerce MCP is a production-ready MCP server that extracts affiliate-ready product entities from newsletter content. It transforms newsletter HTML, plain text, or markdown into structured commerce data for AI agents to use for affiliate marketing, product research, and content monetization.

## Features

- **Product Entity Extraction**: Identifies product names, brands, categories, and prices from newsletter content
- **Sponsorship Detection**: Distinguishes sponsored placements from editorial recommendations
- **Purchase Intent Scoring**: Rates how likely readers are to purchase each mentioned product
- **Affiliate Context**: Extracts CTA language, discount codes, and affiliate signals
- **Section Analysis**: Maps products to specific newsletter sections for context
- **100% F1 Accuracy**: Validated against real newsletter content with ground truth fixtures
- **x402 Micropayments**: Pay-per-call via USDC/Stripe — $0.01/call

## Remote Endpoint

Available as a hosted Cloudflare Workers endpoint — no installation required:

```
https://newsletter-commerce-mcp.sincetoday.workers.dev/mcp
```

Free tier: 200 calls/day, no API key required.

## Tools

- `extract_newsletter_products` — Main extraction tool for newsletter content
- `analyze_newsletter_sponsors` — Identify and score sponsorships and native ads
- `generate_newsletter_products_section` — Format extracted products as shoppable section
- `get_extraction_health` — Check service status and rate limit information

## Use Cases

- Newsletter monetization: identify and optimize affiliate opportunities
- Competitive intelligence: track what products newsletters in your niche promote
- Content automation: auto-generate product roundups from newsletter archives
- Sponsor research: analyze which products get sponsored placement

## Pricing

- **Free tier**: 200 calls/day per agent, no API key required
- **Paid**: $0.01/call via x402 micropayments (USDC on Base or Stripe)
- **API key**: Available for high-volume use cases
