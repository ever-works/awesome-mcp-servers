## telegram-mcp

**Category:** messaging-mcp-servers  
**Brand:** chigwell  
**Source:** https://github.com/chigwell/telegram-mcp  
**License:** Apache-2.0

### Description
telegram-mcp is a Telegram MCP (Model Context Protocol) server powered by the Telethon library. It exposes Telegram functionality to MCP clients, allowing them to access user data, read and manage chats (dialogs, groups, channels), and perform a range of messaging and account operations programmatically.

### Features
- **Telegram integration via MCP**  
  - Acts as an MCP server that bridges MCP-compatible clients with the Telegram API.  
  - Uses Telethon under the hood for Telegram connectivity.

- **Chat & dialog access**  
  - Read chats, including dialogs, groups, and channels.  
  - Retrieve information about existing conversations.

- **Group & channel management**  
  - Manage groups and channels (e.g., administrative operations exposed through the MCP layer).  
  - Adjust chat-related settings where supported by the underlying Telethon/Telegram APIs.

- **Messaging operations**  
  - Send messages to chats, groups, and channels.  
  - Modify existing messages (edit/update).  
  - Handle media messages, including sending and updating media content.  
  - Work with contacts as part of messaging workflows.

- **User data & settings**  
  - Access user-related Telegram data where permitted.  
  - Manage certain Telegram settings via the MCP-exposed operations.

- **Deployment tooling**  
  - Includes a Dockerfile for containerized deployment.  
  - Provides a `docker-compose.yml` for easier multi-service setup.  
  - Example environment configuration via `.env.example`.

- **Client configuration sample**  
  - Contains a `claude_desktop_config.json` example for integrating with Claude Desktop or other MCP-aware clients.

### Pricing
- No pricing information is provided in the available content. The project is open source under the Apache-2.0 license.