## CFBD API MCP Server

**Description**  
An open-source MCP server that integrates the College Football Data (CFBD) API V2 with Claude Desktop, enabling LLMs to query structured college football statistics and related data.

### Features
- Implements a Model Context Protocol (MCP) server for use with Claude Desktop.
- Provides programmatic access to college football statistics and related data from the College Football Data API V2.
- Designed for integration into Claude Desktop via the included `claude_desktop_config.json` configuration file.
- Python-based implementation (targeting Python 3.11).
- Project configured and managed via `pyproject.toml` and `uv.lock` for dependency and environment management.
- Distributed under the MIT License, allowing reuse and modification.

### Technical Details
- **Language:** Python (3.11)
- **Protocol:** Model Context Protocol (MCP)
- **Primary data source:** College Football Data API V2
- **License:** MIT License
- **Repository structure:** Source code under `src/cfbd_mcp_server/`, with additional assets in `images/`.

### Pricing
- **Plan:** Free, open-source
- **Details:** No paid tiers or pricing plans are listed; usage is governed by the MIT License (and the College Football Data API’s own terms).

### Links
- **Source code / documentation:** https://github.com/lenwood/cfbd-mcp-server
- **College Football Data API V2:** https://collegefootballdata.com/