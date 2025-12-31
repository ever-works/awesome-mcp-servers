# Libraria MCP Server

Libraria MCP Server is an MCP (Model Context Protocol) integration that lets you create and embed custom ChatGPT-style assistants on top of your own data, exposing Libraria’s assistant and knowledge-base capabilities through a standard MCP endpoint.

- **Name:** Libraria MCP Server  
- **Category:** AI Integration – MCP Servers  
- **Brand:** Libraria  
- **Slug:** `libraria-mcp-server`  
- **Source URL:** https://mcp.pipedream.com/app/libraria  
- **Featured:** Yes

## Features

- **Custom assistants on your own data**  
  - Create ChatGPT-style assistants powered by your own knowledge base and documents.  
  - Leverages Libraria’s assistant and knowledge-base capabilities via MCP.

- **MCP protocol integration**  
  - Exposes Libraria as an MCP server endpoint that any MCP-compatible client can connect to.  
  - Designed to work with multiple chat clients that support MCP.

- **Static MCP server URL**  
  - Single, static server URL for all clients:  
    - `https://mcp.pipedream.net/v2`  
  - Same URL can be reused across different MCP-enabled applications.

- **Client-agnostic configuration**  
  - Can be added to various chat clients; users select their client and follow specific setup instructions.  
  - Central configuration documentation available via a dedicated configuration page (for detailed integration steps).

- **Rapid setup**  
  - Designed to let users go from data to a working assistant in seconds once the MCP server is connected and authenticated.

- **Hosted via Pipedream Connect**  
  - MCP server hosting and connectivity managed by Pipedream Connect.

## Technical Details

- **MCP endpoint:** `https://mcp.pipedream.net/v2`  
- **Authentication:** Performed when adding the server to an MCP-compatible application (specific mechanism not detailed in the provided content).  
- **Integration surface:** Any MCP client that can register an external MCP server URL.

## Pricing

- Not specified in the provided content. No plan or pricing details are available from the current source.
