# Maestra MCP Server

Automatic transcription and captioning MCP server that exposes Maestra’s audio-to-text capabilities to any MCP-compatible client.

## Overview
- **Type:** MCP server (media processing)
- **Function:** Audio-to-text conversion via automatic transcription and captioning
- **Intended users:** Journalists, students, podcasters, and other users needing fast audio-to-text workflows
- **Provider / Platform:** Runs via Pipedream Connect, exposing Maestra’s capabilities to MCP clients

## Features
- **Automatic transcription**
  - Converts audio to text using Maestra’s transcription engine
  - Designed for fast turnaround (audio to text in minutes)
  - Suitable for spoken content such as interviews, lectures, podcasts, and similar media

- **Automatic captioning**
  - Generates captions from audio for use in video or accessibility workflows
  - Built on the same speech-to-text capabilities as the transcription feature

- **Speech-to-text workflows**
  - Provides Maestra’s speech-to-text capabilities through the MCP protocol
  - Enables integration with any MCP-compatible client or chat application

- **MCP server endpoint**
  - Static MCP server URL usable across clients: `https://mcp.pipedream.net/v2`
  - Authentication handled when adding the server within each client or application

- **Client-agnostic integration**
  - Works with multiple MCP-enabled chat clients
  - Central configuration via the server URL; details and examples available on the configuration page (not included here)

## Usage
- Add the MCP server URL `https://mcp.pipedream.net/v2` to any MCP-compatible application.
- Authenticate within your chosen client when prompted.

## Pricing
- No pricing information is provided in the available content.