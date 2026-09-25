# ThreadFox

ThreadFox is an MCP server and skill for Claude Code and Codex that lets an AI agent work on Reddit through the user's own logged-in Chrome (Microsoft's Playwright Extension), with no Reddit API keys.

## Features

- 26 tools: reddit_rules, reddit_search, reddit_post, reddit_reply, reddit_verify, reddit_read, reddit_comments, reddit_new, reddit_my_posts, reddit_whoami, plus a local SQLite ledger.
- Reads a community's rules before posting.
- Blocks double posts and double replies.
- Resolves posts whose response was lost before any retry.
- Rechecks published posts for removal.

## Availability

- **Pricing:** paid product ($49 one-time) by AMF Indiana; the server is installed by a one-command installer after purchase.
- **Runtime:** Python, runs locally on macOS, Windows and Linux.
- **Website:** https://threadfox.vip/
- **Repository:** https://github.com/amflimited/threadfox (docs, tool reference and audit data; the server source is not included).
