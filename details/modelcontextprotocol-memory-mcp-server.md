## Features

- Persistent memory across chats
- Knowledge graph database for user info
- Configurable with MEMORY_FILE_PATH env

## Setup

Add to claude_desktop_config.json:
```json
{
  "mcpServers": {
    "memory": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-memory"]
    }
  }
}
```
Requires Node.js.

## Pricing

Free and open-source.