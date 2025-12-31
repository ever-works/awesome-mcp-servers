# mcp-server-fetch

**Category:** Data Access & Integration – MCP Servers  
**Tags:** http, web, integration

A Model Context Protocol (MCP) server that lets LLMs fetch web content over HTTP and convert HTML pages into markdown for easier consumption and analysis.

---

## Features

### Web Content Fetching
- Fetches content from arbitrary web pages over HTTP.  
- Converts HTML content to markdown to make it more suitable for LLM processing.
- Supports reading large pages in chunks using `start_index` so models can paginate through content.
- Allows limiting the size of returned content via `max_length`.
- Optional `raw` mode (via tool argument) to control how content is returned.

### MCP Tools
- **`fetch` tool**
  - Parameters:
    - `url`: target webpage to fetch.
    - `max_length`: maximum length of the response content.
    - `start_index`: starting offset for content extraction, enabling incremental/page-wise reading.
    - `raw`: flag/option to adjust raw vs processed output.

### Prompts
- **`url` prompt**: can be used to initiate user-driven fetch requests directly via prompt input.

### Robots.txt Handling
- Obeys `robots.txt` by default for **model-initiated** requests (via tools).  
- Does **not** apply `robots.txt` restrictions by default for **user-initiated** requests (via prompts).
- Behavior can be overridden using the `--ignore-robots-txt` argument in the server configuration.

### User-Agent Customization
- Uses different default user-agents depending on request origin:
  - Model/tool-initiated:
    - `ModelContextProtocol/1.0 (Autonomous; +https://github.com/modelcontextprotocol/servers)`
  - User-initiated (prompt):
    - `ModelContextProtocol/1.0 (User-Specified; +https://github.com/modelcontextprotocol/servers)`
- User-agent can be customized via:
  - `--user-agent=YourUserAgent`

### Proxy Support
- Supports routing requests through a proxy using:
  - `--proxy-url <proxy_address>`

### Integration & Configuration
- Designed to integrate with MCP-compatible clients (e.g., Claude, VS Code MCP clients, others).
- Can be configured specifically for Claude.app by adding it to Claude’s MCP settings (server command and args).

### Debugging
- Compatible with the MCP Inspector for debugging and development.
- Example usage with `uvx`:
  - `npx @modelcontextprotocol/inspector uvx mcp-server-fetch`
- Example usage when developing/installed in a local directory:
  - `cd path/to/servers/src/fetch`
  - `npx @modelcontextprotocol/inspector uv run mcp-server-fetch`

### Extensibility
- Open to contributions for:
  - Adding new tools.
  - Enhancing existing fetch and conversion capabilities.

---

## Installation & Usage

### Using `uv` (recommended)
- No explicit install required when using `uv`.
- Run directly via `uvx`:
  - `uvx mcp-server-fetch`
- Optional: install Node.js for a more robust HTML simplifier used by the server.

### Using `pip`
- Install from PyPI:
  - `pip install mcp-server-fetch`
- Run as a module:
  - `python -m mcp_server_fetch`

### Optional Dependencies
- **Node.js (optional)**
  - If installed, the server uses an alternative, more robust HTML simplifier when processing fetched pages.

---

## Configuration Options (CLI Args)
- `--ignore-robots-txt` – Disable robots.txt checks even for model-initiated tool requests.
- `--user-agent=YourUserAgent` – Override the default user-agent string.
- `--proxy-url <proxy_address>` – Send HTTP requests through a proxy server.

These are typically added to the `args` list in your MCP client/server configuration (e.g., Claude.app settings).

---

## Pricing

- Not specified on the provided page. (Distributed as an open-source Python package on PyPI; any usage costs would depend on your own infrastructure and environment.)

---

## Links

- **Source / Package Page:** https://pypi.org/project/mcp-server-fetch/