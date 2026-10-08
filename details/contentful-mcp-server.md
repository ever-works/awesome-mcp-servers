## Overview

Model Context Protocol (MCP) server for Contentful, enabling AI assistants to manage content, assets, content types, locales, tags, spaces, environments, and AI actions via natural language.

## Getting Started

### Prerequisites
- Node.js
- npm
- Contentful account with Space ID
- Contentful Management API personal access token

### Installation
- One-click installs for Cursor, Claude Desktop, Codex
- Install from source: `git clone https://github.com/contentful/contentful-mcp-server.git`, `cd contentful-mcp-server`, `npm install`, `npm run build`

### Environment Variables

| Variable | Required | Default | Description |
|----------|----------|---------|-------------|
| CONTENTFUL_MANAGEMENT_ACCESS_TOKEN | Yes | - | Contentful Management API token |
| SPACE_ID | Yes | - | Contentful Space ID |
| ENVIRONMENT_ID | No | master | Target environment |
| CONTENTFUL_HOST | No | api.contentful.com | API host |
| NODE_ENV | No | production | Node environment |

### Configuration
Sample for MCP-compatible tools:
```json
{
  "mcpServers": {
    "contentful-mcp": {
      "command": "npx",
      "args": ["-y", "@contentful/mcp-server"],
      "env": {
        "CONTENTFUL_MANAGEMENT_ACCESS_TOKEN": "your-CMA-token",
        "SPACE_ID": "your-space-id",
        "ENVIRONMENT_ID": "master",
        "CONTENTFUL_HOST": "api.contentful.com"
      }
    }
  }
}
```

## Available Tools

### Context & Setup
- `get_initial_context`: Initialize connection and get usage instructions

### Content Types
- `list_content_types`: List all content types
- `get_content_type`: Get detailed content type information
- `create_content_type`: Create new content types
- `update_content_type`: Modify existing content types
- `publish_content_type`: Publish content type changes
- `unpublish_content_type`: Unpublish content types
- `delete_content_type`: Remove content types

### Entries
- `search_entries`: Search and filter entries
- `get_entry`: Retrieve specific entries
- `create_entry`: Create new content entries
- `update_entry`: Modify existing entries
- `publish_entry`: Publish entries (single or bulk)
- `unpublish_entry`: Unpublish entries (single or bulk)
- `delete_entry`: Remove entries

### Assets
- `upload_asset`: Upload new assets
- `list_assets`: List and browse assets
- `get_asset`: Retrieve specific assets
- `update_asset`: Modify asset metadata
- `publish_asset`: Publish assets (single or bulk)
- `unpublish_asset`: Unpublish assets (single or bulk)
- `delete_asset`: Remove assets

### Spaces & Environments
- `list_spaces`: List available spaces
- `get_space`: Get space details
- `list_environments`: List environments
- `create_environment`: Create new environments
- `delete_environment`: Remove environments

### Locales
- `list_locales`: List all locales
- `get_locale`: Retrieve specific locale information
- `create_locale`: Create new locales
- `update_locale`: Modify existing locale settings
- `delete_locale`: Remove locales

### Tags
- `list_tags`: List all tags
- `create_tag`: Create new tags

### AI Actions
- `create_ai_action`: Create custom AI-powered workflows
- `invoke_ai_action`: Invoke an AI action with variables
- `get_ai_action_invocation`: Get AI action invocation details
- `get_ai_action`: Retrieve AI action details
- `list_ai_actions`: List AI actions
- `update_ai_action`: Update AI actions
- `publish_ai_action`: Publish AI actions
- `unpublish_ai_action`: Unpublish AI actions
- `delete_ai_action`: Remove AI actions

## Pricing

Free and open-source under the MIT License.