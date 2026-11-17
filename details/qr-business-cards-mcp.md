# QR Business Cards MCP Server

Remote MCP server that lets AI assistants create digital business-card profiles with QR codes and order printed QR business cards shipped in the US.

## Basic Info

- **Name:** QR Business Cards MCP Server
- **Category:** Business Commerce MCP Servers
- **Source URL:** https://github.com/ajfrai/qr-business-cards-mcp
- **MCP Endpoint:** `https://qr-business-cards.com/api/mcp`
- **Tags:** `qr-codes`, `e-commerce`, `remote`

## Overview

The QR Business Cards MCP Server enables AI assistants to create professional QR business cards for their users. It provides tools to create digital profiles with contact information, social links, and photos, generate QR codes, and order printed business cards shipped to any US address. Remote server with Streamable HTTP transport — no local installation needed.

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
