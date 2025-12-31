# Botsonic MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** Botsonic  
**Slug:** `botsonic-mcp-server`

## Description
Botsonic MCP Server is an MCP server that connects to Botsonic, enabling custom ChatGPT-based AI chatbots trained on your own data. It is designed to be added as a server endpoint within compatible chat clients or applications so that they can communicate with Botsonic via a standardized MCP interface.

## Features
- **Custom ChatGPT-based chatbots**: Integrates with Botsonic to power AI chatbots using ChatGPT, tailored to your own data.
- **Own-data training**: Supports chatbots trained on your specific datasets, documentation, or knowledge base (via Botsonic), enabling more relevant, domain-specific responses.
- **MCP server endpoint**: Exposes a static MCP server URL (`https://mcp.pipedream.net/v2`) that can be added to compatible clients and applications.
- **Single static URL for all clients**: Uses one static MCP URL that works across different clients; authentication is handled when adding the server to each application.
- **Integration with multiple chat clients**: Can be configured in various chat clients (e.g., IDE/chat interfaces that support MCP), with client-specific setup instructions available via the configuration documentation.
- **Configuration through Pipedream**: Uses Pipedream’s interface to connect your Botsonic account and select the appropriate client configuration.
- **Tooling / actions exposure**: Exposes available tools and actions from the Botsonic MCP Server to the client (listed dynamically as “available tools” once connected).

## Configuration Details
- **MCP server URL:** `https://mcp.pipedream.net/v2`  
- **Setup flow:**
  - Connect your Botsonic account via Pipedream.
  - Copy the static MCP server URL.
  - Add the server to your chosen chat client or application.
  - Follow client-specific steps on the configuration page to complete authentication and tool loading.

## Pricing
Pricing information is not provided in the available content.