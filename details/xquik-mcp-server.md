# Xquik MCP Server

## Overview

Xquik is an X/Twitter API and automation platform with an MCP endpoint for agent workflows. It supports tweet search, user lookup, follower exports, media workflows, write actions, giveaway draws, account monitoring, HMAC webhooks, and trending topics.

## Key Details

- **Name:** Xquik MCP Server
- **Category:** Data Access & Integration
- **MCP Server URL:** `https://xquik.com/mcp`
- **Transport:** Streamable HTTP
- **Authentication:** API key bearer token
- **GitHub:** https://github.com/Xquik-dev/x-twitter-scraper
- **Website:** https://xquik.com

## MCP Tools

- **`explore`** - Search the API specification for endpoints, parameters, and response schemas.
- **`xquik`** - Execute supported Xquik API workflows for reads, writes, extractions, monitoring, webhooks, and draws.

## Features

### Read Operations

- Search tweets by keyword, hashtag, or advanced operators
- Look up user profiles and public metrics
- Fetch user tweets, likes, media, and engagement data
- Check mutual followers and related account context

### Write Operations

- Post, delete, reply to, and quote tweets
- Like, retweet, follow, mute, block, and undo those actions
- Send DMs, update profiles, and upload media

### Extraction, Monitoring, and Webhooks

- Export followers, following, replies, quotes, mentions, and search results
- Monitor accounts for new tweets, replies, quotes, and follower changes
- Deliver webhook events signed with HMAC-SHA256

### Additional Workflows

- Track trending topics by region
- Compose tweets with style and scoring helpers
- Run giveaway draws from tweet replies with filters
