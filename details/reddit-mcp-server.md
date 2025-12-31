# Reddit MCP Server

**Category:** Web Search MCP Servers  
**Brand:** Reddit / Pipedream  
**Slug:** `reddit-mcp-server`

## Overview
The Reddit MCP Server is a Model Context Protocol (MCP) server that connects AI agents and chat clients to Reddit. It allows applications to search, read, and interact with subreddit content and discussions programmatically through a static MCP endpoint.

- **Static MCP URL:** `https://mcp.pipedream.net/v2`
- Works with multiple MCP-compatible clients (e.g., ChatGPT via OpenAI) after authentication.

## Features

### MCP Connectivity
- Provides a static MCP server endpoint usable by any compatible client.
- Authentication occurs when adding the server to an application.
- Can be configured via Pipedream’s Reddit app connection flow.

### Reddit Content Interaction Tools (Actions)
The server exposes 5 Reddit actions as tools:

1. **Submit a Post**
   - Create a new post in a specified subreddit.
   - Supports posting content to Reddit communities via MCP.
   - Action source: `components/reddit/actions/submit-a-post/submit-a-post.mjs` (Pipedream GitHub).

2. **Submit a Comment**
   - Submit a new comment or reply to an existing Reddit message/post.
   - Enables conversational interaction with existing Reddit threads.
   - Action source: `components/reddit/actions/submit-a-comment/submit-a-comment.mjs`.

3. **Search Post**
   - Search Reddit posts by title.
   - Useful for content discovery and retrieving relevant discussions.
   - Action source: `components/reddit/actions/search-post/search-post.mjs`.

4. **List Subreddits by Query**
   - List subreddits that match a search query.
   - Helps discover communities related to a topic or interest.
   - Action source: `components/reddit/actions/list-subreddits-by-query/list-subreddits-by-query.mjs`.

5. **List Comments in a Post**
   - Retrieve comments for a specific Reddit post.
   - Enables reading discussion threads and context around a post.
   - Action source: `components/reddit/actions/list-comments-in-a-post/list-comments-in-a-post.mjs`.

### Client Integration
- Can be added to supported chat clients (e.g., ChatGPT/OpenAI) as an MCP server.
- Additional configuration details are available on the Pipedream MCP configuration page.

## Tags
- `social-media`  
- `content-discovery`  
- `communities`

## Pricing
The provided content does not specify any pricing or plans for the Reddit MCP Server.