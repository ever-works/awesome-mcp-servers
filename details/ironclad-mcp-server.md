## Ironclad MCP Server

**Category:** Business & Commerce MCP Servers  
**Tags:** contract-management, CLM, legal

### Overview
The Ironclad MCP Server connects AI/chat clients to Ironclad’s contract lifecycle management platform via the Model Context Protocol (MCP). It provides a single, static MCP endpoint you can add to compatible applications to enable programmatic interaction with Ironclad’s multi-department contract workflows (legal, sales, finance, HR, marketing, procurement, and more).

### MCP Server URL
- Base MCP server URL (static for all clients):
  - `https://mcp.pipedream.net/v2`
- Authentication is performed when adding/configuring the server in your application.

### Features
- **MCP-based integration**
  - Exposes Ironclad’s CLM capabilities through the Model Context Protocol.
  - Designed to be added as a server within MCP-compatible chat or agent clients.

- **Static endpoint**
  - Single shared MCP server URL for all users: `https://mcp.pipedream.net/v2`.
  - Simplifies setup (no per-tenant or per-user URL changes).

- **Authentication on configuration**
  - Users authenticate to Ironclad when they add the MCP server to their app.

- **Multi-department contract coverage**
  - Built to handle all major contract types across:
    - Legal
    - Sales
    - Finance
    - HR
    - Marketing
    - Procurement
    - Other general business contracts

- **Client-agnostic setup**
  - Can be added to different MCP-compatible chat clients.
  - Documentation available via a central configuration page (not client-specific in the description).

### Setup & Integration
- Use the static MCP URL `https://mcp.pipedream.net/v2` in your MCP-compatible client.
- Complete authentication during server addition/configuration in the app.
- Refer to the platform’s configuration documentation for client-specific setup steps.

### Pricing
- Not specified in the provided content.