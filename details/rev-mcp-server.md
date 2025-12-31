# Rev MCP Server

## Overview
Rev MCP Server is an MCP server integration that connects MCP-compatible clients to Rev’s human- and AI-powered speech-to-text services. It enables programmatic creation of transcription, caption, and automated transcription orders using external media links.

- **Category:** Media Processing MCP Servers  
- **Provider / Brand:** Rev (via Pipedream)  
- **Functions:** Transcription, captions, subtitles, automated transcription  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Provides a static MCP server URL (`https://mcp.pipedream.net/v2`) usable with any compatible MCP client.
- Authentication handled when adding the server to the client application.
- Can be added to various chat or MCP-enabled clients (via their configuration for MCP servers).

### Rev Language & Media Services Access
- Connects to Rev’s speech-to-text services powered by both human transcription and AI.
- Supports:
  - Transcripts
  - Captions
  - Subtitles
  - Automated (AI-only) transcription

### Available Tools (Actions)
Three actions are exposed as MCP tools:

1. **Create Transcription Order Using External Link**
   - Submits a new transcription order to Rev.
   - Accepts an external link (URL) pointing to the media to be transcribed.
   - Uses Rev’s transcription service (human and/or AI, per Rev’s standard behavior).

2. **Create Caption Order Using External Link**
   - Submits a new caption order to Rev.
   - Accepts an external media URL for which captions will be generated.
   - Intended for producing caption files aligned with the source media.

3. **Create Automated Transcription Order Using External Link**
   - Submits a new automated (AI-based) transcription order.
   - Accepts an external link to the media file.
   - Uses Rev’s automated transcription service (no manual human transcription step implied).

## Configuration
- Users connect their Rev account via the Pipedream-based configuration flow.
- After connection, the MCP client can invoke the three available actions against the Rev services.
- Additional configuration guidance is available on the referenced configuration page (outside the provided content).

## Pricing
- No pricing details are provided in the available content for the Rev MCP Server or the underlying Rev services.
- Users should refer to Rev or Pipedream directly for current pricing information.