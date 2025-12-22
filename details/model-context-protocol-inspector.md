## Model Context Protocol Inspector

**Description**

Model Context Protocol (MCP) Inspector is an open‑source visual testing and inspection tool for MCP servers. It acts as an MCP client with an interactive UI that lets developers explore, debug, and validate MCP server behavior during development and QA.

**Links**

- Website: https://modelcontextprotocol.io
- Source code: https://github.com/modelcontextprotocol/inspector
- License: MIT

**Category**

- MCP server tools
- Developer utilities / debugging

**Features**

- **Visual inspection of MCP servers**  
  - Connect to MCP servers as a client and view their capabilities in a browser UI.  
  - Inspect available tools, resources, prompts, and other server-provided capabilities.

- **Interactive request testing**  
  - Manually trigger tool calls against an MCP server.  
  - Provide custom arguments and view structured responses.  
  - Iterate quickly on server behavior without going through a production LLM client.

- **Protocol message inspection**  
  - Observe the MCP message exchange between client and server.  
  - Inspect request and response payloads to help diagnose implementation issues.

- **Debugging and validation workflows**  
  - Validate that an MCP server correctly exposes tools, resources, and metadata.  
  - Use the UI to reproduce issues and verify fixes during development and QA.

- **CLI and server components**  
  - CLI tooling to start the inspector and connect it to one or more MCP servers.  
  - Server component that powers the web UI and mediates communication with MCP servers.

- **Local development–friendly**  
  - Designed to run locally alongside MCP servers under development.  
  - Suitable for integrating into existing development workflows and test setups.

**Pricing**

- **Free & open source**  
  - License: MIT  
  - Self-host and run locally at no cost.
