# AssemblyAI MCP Server

MCP Server for AssemblyAI, exposing speech-to-text and speech understanding AI models to MCP clients through a simple API interface.

- **Website / Source**: https://mcp.pipedream.com/app/assemblyai
- **Category**: AI Integration – MCP Servers
- **Slug**: `assemblyai-mcp-server`
- **Provider / Brand**: AssemblyAI (via Pipedream Connect)

## Features

- **MCP Server for AssemblyAI**
  - Exposes AssemblyAI’s speech-to-text and speech understanding AI models to any compatible MCP client.
  - Designed as a simple API interface that can be integrated into MCP-enabled tools and applications.

- **Speech-to-Text Capabilities**
  - Access to AI models that transcribe spoken audio into text.
  - Suitable for use cases that require automated transcription within MCP clients.

- **Speech Understanding Capabilities**
  - Provides access to models that can analyze and understand speech content (e.g., for higher-level understanding beyond raw transcription).

- **Standard MCP Endpoint**
  - Single static MCP server URL for all clients:
    - `https://mcp.pipedream.net/v2`
  - The same URL works across different MCP-compatible chat or automation clients.

- **Authentication at Client Setup**
  - Authentication is performed when adding the MCP server to your application/client (specific method depends on the client configuration).

- **Client-Agnostic Integration**
  - Can be added to various MCP-compatible chat clients and applications.
  - Configuration guidance available via the platform’s configuration page (client-specific setup instructions).

## Configuration

- **MCP Server URL**: `https://mcp.pipedream.net/v2`
- **Setup Flow**:
  - Add the above MCP server URL to your MCP-compatible client.
  - Authenticate when prompted by the client during server addition.
  - Optionally consult the provider’s "Configuration" page for detailed, client-specific steps.

## Pricing

- Not specified in the provided content. Pricing and plan details, if any, would need to be obtained from the AssemblyAI or Pipedream websites directly.