# Rev.ai MCP Server

Accurate speech-to-text APIs exposed as an MCP server for use in MCP-based applications.

- **Website / Source**: https://mcp.pipedream.com/app/rev_ai
- **Category**: Media-processing MCP servers
- **Tags**: speech-to-text, transcript, audio-processing
- **MCP Server URL**: `https://mcp.pipedream.net/v2`

## Features

- **MCP server integration for Rev.ai**
  - Connects Rev.ai’s speech recognition and transcription capabilities to any MCP-compatible client.
  - Designed to expose Rev.ai speech-to-text APIs via the Model Context Protocol.

- **Speech-to-text / transcription support**
  - Provides access to accurate speech-to-text functionality for audio and speech recognition use cases.
  - Suitable for building transcription and audio-processing workflows in MCP-based applications.

- **Static MCP endpoint**
  - Uses a single static server URL: `https://mcp.pipedream.net/v2`.
  - The same URL works across different MCP clients.

- **Client-agnostic integration**
  - Can be added to multiple MCP-compatible chat or agent clients.
  - Configuration is handled at the client level; authentication occurs when adding the server to the application.

- **Central configuration reference**
  - Additional setup and usage details are available via a dedicated configuration page (linked from the app page).

## Authentication

- Authentication is performed when adding the MCP server to your application/client.
- The server URL itself is static; credentials are managed on the client side.

## Pricing

- No pricing information is provided in the available content. Refer to the source page and Rev.ai’s own documentation/pricing for details.