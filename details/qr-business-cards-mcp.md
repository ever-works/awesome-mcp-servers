# QR Business Cards MCP Server

## Overview
The QR Business Cards MCP Server enables AI assistants to create professional QR business cards for their users. It provides tools to create digital profiles with contact information, social links, and photos, generate QR codes, and order printed business cards shipped to any US address. Remote server with Streamable HTTP transport — no local installation needed.

## Key Details
- **Name:** QR Business Cards MCP Server
- **Brand:** QR Business Cards
- **Category:** E-Commerce MCP servers
- **MCP Server URL:** `https://qr-business-cards.com/api/mcp`
- **GitHub:** https://github.com/ajfrai/qr-business-cards-mcp
- **Use Cases:** Creating digital business profiles, generating QR codes, ordering printed business cards

## Features
- **Create Profile**
  - Creates a digital profile page with name, title, email, phone, bio, photo URL, and social links.
  - Returns a public profile URL and QR code URL.
  - Supports two themes: Classic (light) and Noir (dark).

- **Get Profile**
  - Retrieves an existing profile by ID.

- **Get Packages**
  - Lists available printed card packages with pricing.
  - Starter (50 cards), Professional (100 cards), Business (250 cards).

- **Create Order**
  - Places an order for printed QR business cards with a shipping address.
  - Returns a Stripe checkout URL for secure payment.
  - Supports promo codes for discounts.

## Technical Details
- **Transport:** Streamable HTTP (JSON-RPC over HTTPS)
- **Authentication:** None required
- **Safety Annotations:** Includes readOnlyHint, destructiveHint, idempotentHint, and openWorldHint per MCP spec
- **OpenAPI Spec:** https://qr-business-cards.com/api/openapi
- **AI Plugin Manifest:** https://qr-business-cards.com/.well-known/ai-plugin.json
