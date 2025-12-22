## X (Twitter) MCP Server by vidhupv

**Category:** MCP server directories & lists  
**Brand:** x-twitter

### Description
An open-source Model Context Protocol (MCP) server that enables X/Twitter post creation, management, and publishing directly from Claude’s chat interface.

### Features
- MCP server implementation for X/Twitter
- Create new posts on X/Twitter via Claude chat
- Manage existing X/Twitter posts (e.g., prepare and organize content)
- Publish posts to X/Twitter directly from a chat-based workflow
- Designed for integration with Claude Desktop
- Dockerfile included for containerized deployment
- Python-based project with `pyproject.toml` configuration

### Installation / Setup
- **Via Smithery**: Can be installed automatically for Claude Desktop through Smithery (smithery.ai server `x-mcp`).
- **Manual setup**:
  - Edit `claude_desktop_config.json` in the Claude configuration directory (e.g., `~/Library/Application Support/Claude/` on macOS or `%APPDATA%/Claude/` on Windows).
  - Add the MCP server configuration pointing to your local `x-mcp` path.
  - Obtain and configure X/Twitter API credentials.
  - Restart Claude Desktop after configuration changes.
- **Tooling notes**:
  - Uses `uv` for Python environment/command management; troubleshooting suggests reinstalling `uv` via Homebrew and ensuring the command path is correct.

### Pricing
- Open-source project; no pricing or paid plans are specified in the repository.

### Links
- **Source code:** https://github.com/vidhupv/x-mcp