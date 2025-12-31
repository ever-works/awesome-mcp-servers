# Microsoft Dataverse MCP Server

## Overview
Microsoft Dataverse MCP Server is an integration that connects Microsoft Dataverse (the Microsoft enterprise data platform behind many Copilot experiences) to MCP-compatible agents and chat clients. It exposes enterprise data stored in Dataverse so copilots and agents can use it for grounded, data-aware interactions.

- **Category:** Data Access / Integration MCP Server  
- **Brand:** Microsoft  
- **Use cases:** Access Microsoft Dataverse data from MCP agents, build actionable copilots on top of Dataverse, integrate enterprise data into chat-based workflows.

## Features
- **MCP server endpoint**  
  - Provides a static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.  
  - Same URL can be reused across different MCP-compatible applications; authentication is handled when adding the server to each app.

- **Microsoft Dataverse integration**  
  - Connects to Microsoft Dataverse as the underlying enterprise data platform.  
  - Enables grounded access to enterprise data for copilots and MCP agents.  
  - Designed to help make copilots “actionable” by tying them to real organizational data in Dataverse.

- **Client-agnostic setup**  
  - Can be added to multiple chat clients that support MCP.  
  - Per-client configuration instructions are linked from the interface (“Select your chat client to learn how to get started”).

- **Configuration workflow**  
  - Connect a Microsoft Dataverse account through the Pipedream interface.  
  - After account connection, select the client and copy the MCP server URL.  
  - Authentication occurs when the server is added to the chosen client or application.

- **Tooling / actions exposure**  
  - Exposes Dataverse-related tools and actions to MCP agents (listed in the UI as “Available tools”).  
  - Tools are dynamically loaded; intended for querying or operating on Dataverse data (exact list not shown in the provided content).

## Pricing
Pricing details are not provided in the available content.