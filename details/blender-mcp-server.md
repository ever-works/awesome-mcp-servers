## Features

- Two-way communication with Claude AI
- Create/modify/delete 3D objects
- Apply/modify materials and colors
- Scene inspection
- Run Python code in Blender

## Requirements

- Blender 3.0+
- Python 3.10+
- uv package manager

## Setup for Claude Desktop

Add to claude_desktop_config.json:
```json
{
  "mcpServers": {
    "blender": {
      "command": "uvx",
      "args": ["blender-mcp"]
    }
  }
}
```
For Cursor: `uvx blender-mcp`

## Pricing

Free and open-source.