## Overview

PostEverywhere is a social media scheduling and publishing platform with a hosted MCP server. It lets AI assistants schedule and publish posts across Instagram, TikTok, YouTube, LinkedIn, Facebook, X, Threads, Pinterest, Bluesky, Discord, and Telegram from natural language.

## Features

- Schedule and publish across 11 social platforms
- Drafts with human-in-the-loop review (create a draft, then schedule it)
- AI caption generation tuned per platform
- Campaigns, bulk operations, and media upload
- Analytics and webhooks
- Hosted connector (OAuth 2.1), an npm package, and a full REST API

## Setup

Hosted: connect at https://mcp.posteverywhere.ai/mcp (OAuth 2.1, no API key to copy). Local: run `npx -y @posteverywhere/mcp` with a POSTEVERYWHERE_API_KEY from Settings, Developers. Estimated setup time: 2 to 5 minutes.

## Pricing

Paid SaaS with a 7 day free trial. Plans start at $19 per month.

## Considerations

- Managed cloud service, not self-hosted
- Requires a PostEverywhere account
- Platforms are connected via OAuth inside the app

## Best For

Teams and creators who want one managed MCP server to schedule and publish across all major social platforms without self-hosting.
