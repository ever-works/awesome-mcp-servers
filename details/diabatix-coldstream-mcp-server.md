## Diabatix ColdStream MCP Server

**Category:** Development Tools → MCP Servers  
**Brand:** diabatix  
**Slug:** diabatix-coldstream-mcp-server

### Description
The Diabatix ColdStream MCP Server is an integration that exposes Diabatix ColdStream’s generative design capabilities for thermal and flow topology optimization through the Model Context Protocol (MCP). It allows MCP-compatible tools and chat clients to interact with ColdStream for tasks such as optimal heat sink design.

### Features
- **MCP-compatible server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Can be added to any supported MCP client or application.

- **Integration with Diabatix ColdStream**  
  - Connects to a Diabatix ColdStream account.  
  - Exposes ColdStream’s generative design engine focused on thermal and flow topology optimization.  
  - Supports use cases such as optimal heat sink and cooling system design.

- **Client configuration**  
  - Guided flow to connect a Diabatix ColdStream account.  
  - Selection of an MCP client / chat client to see client-specific setup instructions.  
  - Central configuration documentation available via a dedicated Configuration page.

- **Tool access (via MCP)**  
  - Designed to surface available tools and actions from Diabatix ColdStream into MCP clients (tool listing is dynamically loaded in the UI).

### Technical Details
- **MCP server base URL:** `https://mcp.pipedream.net/v2`  
- **Authentication:** Performed when adding the server to a client (details handled in client-specific setup, not exposed in the snippet).  
- **Host platform:** Pipedream MCP integration.

### Pricing
Pricing information is not provided in the available content.