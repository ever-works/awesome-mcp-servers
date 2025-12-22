## Discord MCP Server

**Category:** MCP server directories & lists  
**Brand:** Discord  
**Source:** https://github.com/v-3/discordmcp

### Overview
Discord MCP Server is a Model Context Protocol (MCP) server that lets LLMs (such as Claude) interact with Discord through a bot. It connects to Discord guilds via the Discord API so MCP‑compatible clients can read from and send messages to Discord channels while preserving user control and permissions.

### Features
- **Message sending**
  - Send messages to Discord channels via the MCP server
  - Works with both channel names and channel IDs

- **Message reading**
  - Read recent messages from Discord channels
  - Uses Discord’s API to fetch channel history

- **Server & channel handling**
  - Automatic discovery of available Discord servers (guilds)
  - Automatic discovery of channels within those servers
  - Supports addressing channels by name or ID

- **Error handling & validation**
  - Input validation for channel targeting and operations
  - Proper error handling for failed API calls or invalid configuration

- **MCP & client integration**
  - Implements the Model Context Protocol for tool-based LLM workflows
  - Designed for use with Claude for Desktop via `claude_desktop_config.json`
  - Exposes an MCP server endpoint that can be launched via Node.js

### Prerequisites
- Node.js 16.x or higher
- A Discord bot token
- The bot must be invited to the target Discord server(s) with at least:
  - Read Messages / View Channels
  - Send Messages
  - Read Message History

### Setup (High-Level)
- Clone the repository from GitHub
- Install dependencies with `npm install`
- Create a `.env` file containing `DISCORD_TOKEN=your_discord_bot_token_here`
- Build the server with `npm run build`
- Configure Claude for Desktop to use the MCP server in `claude_desktop_config.json`

### Pricing
- Pricing details are not specified in the provided content (open GitHub repository; refer to the project’s license and documentation for usage terms).