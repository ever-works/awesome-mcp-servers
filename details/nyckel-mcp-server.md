# Nyckel MCP Server

## Overview
Nyckel MCP Server is an integration that exposes Nyckel’s fast image and text classification models through the Model Context Protocol (MCP). It allows users to train custom classification models with their own labels and access them from compatible MCP clients via a single static server URL.

## Features
- **MCP-based access**: Provides an MCP server endpoint that can be added to any compatible chat client or application.
- **Static server URL**: Uses a single, reusable endpoint for all clients:
  - `https://mcp.pipedream.net/v2`
- **Image classification**: Supports building and using custom image classification models.
- **Text classification**: Supports building and using custom text classification models.
- **Custom labels**: Users can define arbitrary labels for their classification tasks.
- **No ML expertise required**: Designed so users can train and deploy models without machine learning experience.
- **Fast model inference**: Optimized for quick classification of images and text (as described by Nyckel).
- **Client-agnostic configuration**: Works with multiple MCP-compatible chat clients; configuration is documented on a central configuration page.

## Usage
- Add the MCP server to your MCP-compatible app or chat client using the static URL: `https://mcp.pipedream.net/v2`.
- Authenticate within your client when prompted.
- Configure and use Nyckel’s image and text classification models via the MCP integration.

## Pricing
- No pricing information is provided in the available content. Refer to Nyckel or Pipedream for current pricing details.