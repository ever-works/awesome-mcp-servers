# TwitterAPI.io MCP Server

[TwitterAPI.io MCP Server](https://github.com/kaitoInfra/twitterapi-io-mcp-server) is the official hosted Model Context Protocol server for [TwitterAPI.io](https://twitterapi.io), exposing Twitter / X data as 12 read-only tools for AI agents.

## Quick start

Drop this into your MCP client config:

```json
{
  "mcpServers": {
    "twitter": {
      "url": "https://mcp.twitterapi.io/mcp"
    }
  }
}
```

Restart your client (Claude Desktop, Cursor, Codex, or any MCP-compatible client). Your agent now has access to live Twitter / X data via the [TwitterAPI.io](https://twitterapi.io) backend.

## Tools

1. `search_tweets` — keyword / hashtag search with date filters
2. `get_user_info` — profile lookup by username
3. `get_user_timeline` — recent tweets from an account
4. `get_user_followers` — follower list
5. `get_user_following` — following list
6. `get_tweet_by_id` — single tweet lookup
7. `get_replies` — conversation thread expansion
8. `get_quotes` — quote-tweet chain
9. `get_retweeters` — accounts that retweeted
10. `search_users` — user search by keyword
11. `get_trending_topics` — current trending topics
12. `get_tweet_metrics` — engagement metrics

## Authentication

Pass your TwitterAPI.io API key via environment variable `TWITTERAPI_IO_API_KEY` on the MCP client side. Get a key (with free tier) at [twitterapi.io](https://twitterapi.io).

## Use cases

- Brand monitoring agents that scan Twitter conversation
- Academic research collecting tweet corpora
- Crypto / finance signal extractors
- AI assistants surfacing real-time tweet context inside chat
- Newsletter / digest pipelines summarising X discussion

## Pricing

Pay-per-call: $0.15 per 1,000 tweet-search results, free tier on signup, no monthly subscription. Detailed pricing at [twitterapi.io/pricing](https://twitterapi.io/pricing).

## Links

- Site: [twitterapi.io](https://twitterapi.io)
- Docs: [twitterapi.io/docs](https://twitterapi.io/docs)
- Pricing: [twitterapi.io/pricing](https://twitterapi.io/pricing)
- Source: [github.com/kaitoInfra/twitterapi-io-mcp-server](https://github.com/kaitoInfra/twitterapi-io-mcp-server)
- npm: [@kaitoinfra/twitterapi-io-mcp-server](https://www.npmjs.com/package/@kaitoinfra/twitterapi-io-mcp-server)
- Official MCP Registry: `io.github.kaitoInfra/twitterapi-io-mcp-server` (active since 2026-05-23)

## License

MIT
