## Overview

AWS Core MCP Server enables AI agents to interact with essential AWS services.

## Features

- Supports stdio transport
- Configurable log levels via FASTMCP_LOG_LEVEL
- Global or project-specific configuration

## Installation

Example for macOS/Linux:
```json
{
  "command": "uvx",
  "args": ["awslabs.core-mcp-server@latest"],
  "env": {
    "FASTMCP_LOG_LEVEL": "ERROR"
  }
}
```

## Pricing

Free and open-source under the Apache 2.0 license.