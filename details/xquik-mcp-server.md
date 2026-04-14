# Xquik MCP Server

## Overview

Xquik is a real-time X (Twitter) data platform that exposes 122 REST API endpoints through 2 MCP tools. It supports tweet search, user lookup, bulk data extraction, write actions, giveaway draws, account monitoring, HMAC webhooks, and trending topics.

## Key Details

- **Name:** Xquik MCP Server
- **Category:** Data Access & Integration
- **MCP Server URL:** `https://xquik.com/mcp`
- **Transport:** StreamableHTTP
- **Authentication:** API key (Bearer token)
- **GitHub:** https://github.com/Xquik-dev/x-twitter-scraper
- **Website:** https://xquik.com

## MCP Tools

- **`explore`** — Search the API specification to discover endpoints, parameters, and response schemas. Free, read-only.
- **`xquik`** — Execute any of the 122 REST API endpoints. Covers reads, writes, extractions, monitoring, webhooks, draws, and more.

## Features

### Read Operations
- Tweet search (keyword, hashtag, advanced operators)
- User profile lookup (bio, followers, following, verified status)
- User tweets, likes, and media feeds
- Tweet engagement data (favoriters, retweeters)
- Mutual followers check
- Bookmarks, notifications, home timeline, DM history

### Write Operations
- Post/delete tweets, reply, quote tweet
- Like/unlike, retweet/unretweet
- Follow/unfollow, mute/unmute, block/unblock
- Send DMs, update profile, upload media

### Bulk Extraction (23 Tools)
- Replies, retweets, quotes, mentions, posts
- Followers, following, verified followers
- Favoriters, retweeters, community members
- Tweet search, people search, list members
- User likes, user media, articles, threads

### Monitoring & Webhooks
- Track accounts for new tweets, replies, quotes, follower changes
- HMAC-SHA256 signed webhook delivery
- Telegram integration for real-time notifications

### Additional
- Trending topics by region + 7 free Radar news sources
- Algorithm-optimized tweet composer with scoring
- Giveaway draws from tweet replies with 11 filter options
- Credits system with pay-per-use ($0.00015/read)

## Pricing

- **Starter:** $20/month (reads from $0.00015/call)
- **Pro:** $99/month
- **Business:** $199/month
- **Pay-per-use:** Credit top-ups ($10 minimum) or MPP on-chain payments (no account needed)
