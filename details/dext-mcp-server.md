# Dext MCP Server

**Category:** Finance & Market Data MCP Servers  
**Brand:** Dext

Cloud accounting MCP server that lets MCP-compatible agents connect to Dext’s cloud accounting and real-time financial data services via a static MCP endpoint.

---

## Features

- **MCP server for Dext**
  - Exposes Dext’s cloud accounting capabilities through the Model Context Protocol (MCP).
  - Designed for use by MCP-compatible agents and chat clients.

- **Static MCP endpoint**
  - Single MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
  - URL is static; authentication is handled when you add the server to your application.

- **Dext account integration**
  - Connect a Dext account from the MCP server UI.
  - Select a specific client within your Dext account to work with.

- **Real-time financial data access**
  - Integrates with Dext’s real-time data services for up-to-date accounting and financial information (as provided by Dext).

- **Tooling for agents**
  - Provides “tools” / “actions” that MCP agents can call programmatically (listed dynamically as “Available tools”).
  - Tools are discoverable by MCP-compatible chat clients once the server is added.

- **Multi-client support**
  - One MCP URL works for every Dext client; you choose which client to operate on after connecting your account.

- **Configuration guidance**
  - Instructions for adding the server to various chat clients.
  - A dedicated configuration page for detailed setup steps.

---

## Integration & Usage

- Add the MCP server URL to your MCP-compatible application or chat client.
- Authenticate with Dext when prompted.
- Select the target Dext client within your account.
- Use the exposed MCP tools to access or act on Dext financial and accounting data.

---

## Pricing

- No pricing information is provided in the available content. The cost or billing model for using the Dext MCP Server (or underlying Dext/Pipedream services) is not specified here.