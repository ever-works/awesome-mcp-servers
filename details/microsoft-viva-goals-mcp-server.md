# Microsoft Viva Goals MCP Server

Microsoft Viva Goals MCP Server provides MCP-based access to Microsoft Viva Goals, enabling teams to align and track business objectives and key results (OKRs) within automated workflows.

**Website:** https://mcp.pipedream.com/app/microsoft_viva_goals  
**Category:** Project Management MCP Servers  
**Brand:** Microsoft  
**Tags:** okr, goal-tracking, analytics

## Features

- **MCP-based access to Viva Goals**  
  - Exposes Microsoft Viva Goals through the Model Context Protocol (MCP) for integration with compatible applications and AI assistants.

- **Centralized goal management**  
  - Designed to manage business goals, objectives, and key results from a single, central location.

- **Team alignment support**  
  - Helps align teams around shared goals and track progress toward outcomes.

- **Static MCP server endpoint**  
  - Uses a single, static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.

- **Authentication at client level**  
  - Authentication is handled when adding the server to your application or chat client, enabling secure access per user/client.

- **Multi-client compatibility**  
  - Can be added to different chat or MCP-compatible clients (e.g., AI assistants, developer tools) by configuring the server URL and authentication.

- **Workflow automation support**  
  - Intended to be used inside automated workflows so goal data from Viva Goals can be read or updated programmatically through MCP tools (specific tools are loaded dynamically in the UI).

## Configuration

- Copy the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add the server to your MCP-compatible application or chat client and complete authentication as prompted.

## Pricing

- Not specified in the provided content.