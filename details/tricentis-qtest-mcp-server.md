# Tricentis qTest MCP Server

MCP Server integration for Tricentis qTest, providing MCP tools with access to scalable test management, operations, and analytics across the software development lifecycle.

- **Website**: https://mcp.pipedream.com/app/tricentis_qtest  
- **Category**: Testing & Debugging Tools  
- **Tags**: test-management, analytics, quality-assurance

## Description

Tricentis qTest MCP Server is an MCP-compatible endpoint hosted by Pipedream that connects MCP tools and chat clients to Tricentis qTest. It exposes actions for managing requirements and defects, enabling centralized test management and quality operations with visibility across the SDLC.

## Features

### MCP Server & Connectivity
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
- Works as a generic MCP server that can be added to compatible applications and chat clients.  
- Authentication occurs when adding the server to your application.  
- Integrates with Tricentis qTest via Pipedream.

### Tricentis qTest Actions (Tools)
The MCP server exposes 6 actions as tools for Tricentis qTest:

1. **Create Requirement**
   - Create a new requirement in Tricentis qTest.

2. **Get Requirement**
   - Retrieve details of an existing requirement.

3. **Update Requirement**
   - Update fields and information for an existing requirement.

4. **Submit Defect**
   - Submit a new defect (bug) to Tricentis qTest.

5. **Get Defect**
   - Fetch detailed information about a specific defect.

6. **Update Defect**
   - Modify an existing defect’s attributes.

### Usage Context
- Designed for web and app development workflows.  
- Centralizes testing-related entities (requirements and defects) so they can be managed from MCP-enabled clients (e.g., chat-based or tool-based automations).  
- Supports test management, operations, and analytics by enabling programmatic access to core qTest objects.

## Configuration
- Connect a Tricentis qTest account in Pipedream.  
- Use the static MCP server URL when adding the server to your client or application.  
- Configuration details and client-specific setup instructions are available on Pipedream’s configuration page.

## Pricing

No pricing or plan information is provided in the available content.