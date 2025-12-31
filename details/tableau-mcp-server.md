# Tableau MCP Server

**Category:** Data Visualization  
**Brand:** Tableau  
**Source:** https://mcp.pipedream.com/app/tableau

## Description
The Tableau MCP Server is an integration that exposes Tableau’s visual analytics and data exploration capabilities to MCP-based applications. It connects to a Tableau site via a static MCP server URL, enabling applications (including chat clients like ChatGPT) to interact with Tableau resources programmatically.

## Features

### MCP Server Integration
- Provides a static MCP server URL usable by any compatible client:
  - `https://mcp.pipedream.net/v2`
- Authentication occurs when adding the server to your application, allowing secure access to Tableau resources.
- Can be integrated with various chat clients (e.g., ChatGPT via OpenAI) using configuration guides.

### Tableau Account Connectivity
- Connects to a Tableau account and specified site.
- Lets you manage Tableau content and resources through MCP-based apps after signing in and configuring the connection.

### Available Tools (Actions)
Three primary actions are exposed as MCP tools:

1. **Query Projects**  
   - Returns a list of projects on a specified Tableau site.  
   - Useful for:  
     - Discovering existing project structure.  
     - Enumerating available workspaces for dashboards, workbooks, and other assets.

2. **Download PDF**  
   - Downloads images of the sheets of a workbook as a PDF file.  
   - Useful for:  
     - Exporting workbook sheets for sharing or offline review.  
     - Automating PDF generation of Tableau visualizations through an MCP client.

3. **Create Project**  
   - Creates a new project on a specified Tableau site.  
   - Supports creation of **project hierarchies** by specifying a parent project.  
   - Useful for:  
     - Organizing workbooks and dashboards into structured folders.  
     - Automating environment or folder setup for teams and projects.

## Integration & Configuration
- The same MCP server URL works for all clients; configuration steps differ per client (e.g., ChatGPT) and are provided via a separate configuration guide.
- Once configured, MCP-based applications can call the exposed actions to list projects, create new ones, and export workbooks to PDF.

## Pricing
No pricing information is provided in the available content for the Tableau MCP Server. Pricing may depend on underlying Tableau or Pipedream/Workday services and is not specified here.