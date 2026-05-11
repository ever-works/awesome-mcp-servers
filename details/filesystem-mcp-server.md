# Filesystem MCP Server

A Node.js implementation of the Model Context Protocol (MCP) that exposes filesystem capabilities to AI agents through a standardized interface.

## Features

- **File Operations**:
  - `read_text_file`: Read complete file contents as UTF-8 text, with optional head/tail line selection
  - `read_media_file`: Read image/audio files and return base64-encoded data with MIME type
  - `read_multiple_files`: Read several files simultaneously; failures don't halt the operation
  - `write_file`: Create or overwrite files (use with caution)
  - `edit_file`: Make selective edits using pattern matching, with whitespace normalization, indentation preservation, and dry-run mode
  - `get_file_info`: Retrieve detailed metadata (size, timestamps, permissions, type)

- **Directory Operations**:
  - `create_directory`: Create a directory and any missing parents; silent if already exists
  - `list_directory`: List contents with [FILE] or [DIR] prefixes
  - `list_directory_with_sizes`: List contents including file sizes, sortable by name or size
  - `move_file`: Move or rename files/directories; fails if destination exists
  - `directory_tree`: Get recursive JSON tree structure of directory contents

- **Search & Navigation**:
  - `search_files`: Recursive glob-style search with include/exclude patterns

- **Access Control**:
  - `list_allowed_directories`: Show directories the server is permitted to access
  - Dynamic directory access control via command-line arguments or MCP Roots (recommended)
  - Roots protocol allows clients to update allowed directories at runtime without server restart
  - All operations restricted to allowed directories; server requires at least one allowed directory to start

- **Tool Annotations (MCP Hints)**:
  - Read‑only tools: `read_text_file`, `read_media_file`, `read_multiple_files`, `list_directory`, `list_directory_with_sizes`, `directory_tree`, `search_files`, `get_file_info`, `list_allowed_directories`
  - Write tools with idempotent/destructive hints:
    - `create_directory`: idempotent (re‑creating same dir is a no‑op)
    - `write_file`: destructive (overwrites existing file)
    - `edit_file`: destructive (re‑applying edits can fail or double‑apply)
    - `move_file`: destructive (deletes source file)

## Directory Access Control

The server supports two methods for specifying allowed directories:

1. **Command‑line Arguments**:
   ```
   mcp-server-filesystem /path/to/dir1 /path/to/dir2
   ```

2. **MCP Roots (Recommended)**:
   - Clients that support the Roots protocol can dynamically update allowed directories
   - On initialization, server requests roots via `roots/list` and replaces all allowed directories
   - Runtime updates via `roots/list_changed` notifications
   - If started without arguments and client doesn’t support Roots (or provides empty roots), server throws an error on init

All filesystem operations are confined to the allowed directories; use `list_allowed_directories` to inspect current access.

## Usage

### Docker
```json
{
  "mcpServers": {
    "filesystem": {
      "command": "docker",
      "args": [
        "run",
        "-i",
        "--rm",
        "--mount", "type=bind,src=/Users/username/Desktop,dst=/projects/Desktop",
        "--mount", "type=bind,src=/path/to/other/allowed/dir,dst=/projects/other/allowed/dir,ro",
        "--mount", "type=bind,src=/path/to/file.txt,dst=/projects/path/to/file.txt",
        "mcp/filesystem",
        "/projects"
      ]
    }
  }
}
```

### NPX
```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": [
        "-y",
        "@modelcontextprotocol/server-filesystem",
        "/Users/username/Desktop",
        "/path/to/other/allowed/dir"
      ]
    }
  }
}
```

### Windows (cmd /c)
```json
{
  "mcpServers": {
    "filesystem": {
      "command": "cmd",
      "args": [
        "/c",
        "npx",
        "-y",
        "@modelcontextprotocol/server-filesystem",
        "/Users/username/Desktop",
        "/path/to/other/allowed/dir"
      ]
    }
  }
}
```

### VS Code
- **User Configuration**: Add to user‑level MCP config via `MCP: Open User Configuration`
- **Workspace Configuration**: Add to `.vscode/mcp.json`

Mount directories to `/projects`; use `ro` flag for read‑only mounts.

## Build
```sh
docker build -t mcp/filesystem -f src/filesystem/Dockerfile .
```

## License
Licensed under the MIT License – free to use, modify, and distribute.
