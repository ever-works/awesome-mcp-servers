# Sigma MCP Server

**Category:** Data Analysis & Exploration MCP Servers  
**Brand:** Sigma Computing

Sigma MCP Server is an MCP-compatible integration that connects Sigma’s cloud analytics platform (with a spreadsheet-like UI) into MCP-capable chat clients and workflows via Pipedream.

---

## Features

### MCP Server Integration
- Provides a static MCP server URL for integration: `https://mcp.pipedream.net/v2`.
- Works with any MCP-compatible client (e.g., ChatGPT / OpenAI clients) once authenticated.
- Authentication handled when adding the server to your application.

### Sigma Cloud Analytics Connectivity
- Connects to your Sigma account through Pipedream.
- Enables use of Sigma’s cloud-scale analytics and spreadsheet-like interface through MCP-based tools and workflows.

### Available Tools (Actions)
The Sigma MCP Server currently exposes three main actions as tools:

1. **List Datasets**  
   - Returns a list of available datasets in Sigma.  
   - Useful for discovering what data is accessible before running analyses or building workbooks.

2. **Create Workbook**  
   - Creates a new blank workbook in Sigma.  
   - Allows programmatic or conversational creation of workbooks as part of workflows.

3. **Create Team**  
   - Creates a new team within Sigma.  
   - Supports organizational setup and user grouping directly via MCP tools.

### Configuration & Client Support
- "Configure Sigma" flow to connect and manage Sigma accounts via Pipedream.
- Client-specific setup guidance (e.g., ChatGPT/OpenAI) available through the configuration pages.

---

## Pricing

No pricing information is provided in the available content. Refer to Sigma and/or Pipedream official sites for details on product and integration pricing.

---

## Links
- Sigma MCP Server page: https://mcp.pipedream.com/app/sigma
- Sigma documentation: https://docs.sigmacomputing.com/
- MCP server URL: `https://mcp.pipedream.net/v2`
- Action documentation:
  - List Datasets: https://github.com/PipedreamHQ/pipedream/blob/master/components/sigma/actions/list-datasets/list-datasets.mjs
  - Create Workbook: https://github.com/PipedreamHQ/pipedream/blob/master/components/sigma/actions/create-workbook/create-workbook.mjs
  - Create Team: https://github.com/PipedreamHQ/pipedream/blob/master/components/sigma/actions/create-team/create-team.mjs