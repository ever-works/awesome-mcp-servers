## Overview

folder-mcp implements the Model Context Protocol (MCP) standard to allow LLMs to interact with local folders securely via stdio transport.

## Features

- **Secure File Access**: Path validation, prevents directory traversal, supports various file types and encodings.
- **File System Operations**: Recursive listing, glob-based searching, folder metadata.
- **Exclusions**: Automatically skips node_modules, .git, and cache directories.
- **MCP Tools**:
  - `get_status`: System status check.
  - `read_file`: Read file contents by relative path.
  - `search_files`: Find files by pattern (e.g., '*.md').
  - `list_files`: Recursive file listing.
  - `get_folder_info`: Folder stats and metadata.
- TypeScript with full type safety, clear error handling.

## Installation

```
git clone https://github.com/okets/folder-mcp.git
cd folder-mcp
npm install
npm run build
```

## Configuration

Uses `config.yaml` for embeddings (Ollama support: nomic-v1.5, mxbai-large, etc.), caching, text processing, logging, and dev options.

## Usage

Configure in MCP clients like Claude Desktop:

```json
{
  "mcpServers": {
    "folder-mcp": {
      "command": "node",
      "args": ["dist/mcp-server.js", "/path/to/folder-mcp"],
      "env": {}
    }
  }
}
```

Note: Logs to stderr only for stdio compatibility.

## Pricing

Free and open-source under MIT License.

## Current Status

Version 1.0: Basic MCP server (13/30 features). Upcoming: Semantic search, embeddings, vector search.