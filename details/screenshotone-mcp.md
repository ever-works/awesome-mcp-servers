# ScreenshotOne MCP

An official Model Context Protocol (MCP) server for integrating the ScreenshotOne webpage rendering API, enabling LLMs and MCP-compatible clients to generate website screenshots on demand.

- **Website:** https://github.com/screenshotone/mcp/
- **Category:** Media Processing MCP Servers
- **Tags:** screenshot, web, image-generation
- **License:** MIT

## Features

### MCP Integration
- Implements an MCP (Model Context Protocol) server compatible with MCP-capable clients (e.g., Claude for Desktop).
- Exposes ScreenshotOne’s webpage rendering API through a standardized MCP tool interface.

### Tools
- **`render-website-screenshot`**  
  Primary tool provided by the server to request and generate website screenshots via the ScreenshotOne API.

### Usage & Integration
- **Build process**  
  - Project includes `package.json`, `package-lock.json`, and `tsconfig.json` for Node/TypeScript builds.
  - Requires installing dependencies and building the project before use.
- **API key support**  
  - Uses a ScreenshotOne API key obtained from the ScreenshotOne service to authenticate and authorize screenshot requests.
- **Claude for Desktop integration**  
  - Can be configured for use with Claude for Desktop by adding an MCP server entry to `~/Library/Application Support/Claude/claude_desktop_config.json`.
- **Standalone / other projects**  
  - Can be run as a standalone MCP server or integrated into other MCP-enabled environments.

## Technical

- Written as a Node/TypeScript project (presence of `tsconfig.json`, `package.json`).
- Source code located under the `src` directory in the repository.

## Pricing

- The MCP server implementation itself is open source under the MIT License.  
- Any usage-based or subscription pricing would come from the underlying ScreenshotOne API (not specified in this repository content).