# Competitor Ads (Apify-hosted)

Hosted MCP server for competitor ad research: creatives from the Google Ads Transparency Center and the LinkedIn Ad Library by domain, advertiser or keyword.

## Basic Info

- **Name:** Competitor Ads (Apify-hosted)
- **Category:** Marketing
- **Source URL:** https://apify.com/dheerajitbhu/google-ads-transparency?utm_source=ever-works&utm_medium=directory&utm_campaign=google-ads-transparency
- **MCP Endpoint:** `https://mcp.apify.com/?tools=dheerajitbhu/google-ads-transparency,dheerajitbhu/linkedin-ad-library`
- **MCP Registry:** `io.github.dheerajitbhu/competitor-ads`
- **Tags:** `advertising`, `marketing`, `research`, `remote`

## Features

- Google Ads Transparency Center: ads for an advertiser or domain, with format, first and last shown dates, requested region, image or preview URL and a cite-back link ([Actor page](https://apify.com/dheerajitbhu/google-ads-transparency?utm_source=ever-works&utm_medium=directory&utm_campaign=google-ads-transparency)).
- LinkedIn Ad Library: ads by advertiser or keyword, with advertiser name, format, text, image, headline and CTA when ad details are fetched ([Actor page](https://apify.com/dheerajitbhu/linkedin-ad-library?utm_source=ever-works&utm_medium=directory&utm_campaign=linkedin-ad-library)).
- Typed JSON rows; every call accepts a `maxChargeUsd` spend cap.

## Setup

- Remote Streamable HTTP server, no install. Add the endpoint above to any MCP client that supports remote servers (Claude, Cursor, VS Code, ChatGPT).
- Auth: Apify OAuth sign-in, or `Authorization: Bearer <Apify API token>`.
- Pricing: pay per result ($0.99 per 1,000 ads) plus $0.001 per run, billed to your own Apify account.