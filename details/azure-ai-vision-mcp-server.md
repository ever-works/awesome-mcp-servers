# Azure AI Vision MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** Microsoft Azure  
**Slug:** `azure-ai-vision-mcp-server`

## Overview
Azure AI Vision MCP Server exposes Microsoft Azure’s computer vision capabilities—such as image analysis and OCR—to MCP-compatible clients via Pipedream. It allows applications to analyze images and extract text without requiring machine learning expertise.

## Features
- **Unified computer vision service**  
  - Access Azure AI Vision capabilities through a single MCP server endpoint.

- **Optical Character Recognition (OCR)**  
  - Extracts text from images using Azure AI Vision OCR.  
  - Available as an MCP tool/action: **Extract Text from Image**.

- **Image analysis (via Azure AI Vision)**  
  - Supports general image analysis capabilities from Azure AI Vision (e.g., image tagging and related vision features) when used through Azure’s APIs.

- **Face-related capabilities (via Azure AI Vision)**  
  - Can leverage Azure AI Vision’s responsible facial recognition / face detection features through the underlying Azure service where configured.

- **MCP server endpoint**  
  - Static MCP server URL usable by multiple clients:  
    - `https://mcp.pipedream.net/v2`
  - Authentication handled when adding the server to your application.

- **Client integration**  
  - Can be added to compatible chat clients (e.g., ChatGPT / OpenAI clients that support MCP).  
  - Configuration guidance available via Pipedream’s configuration pages.

## Available Tools / Actions
- **Extract Text from Image**  
  - Description: Extracts text from a provided image using Azure AI Vision OCR.  
  - Implementation reference: Pipedream action `extract-text-from-image` for Azure AI Vision.

## Integration & Configuration
- Connect your Azure AI Vision account via Pipedream to use the MCP server.  
- After connecting, select your client (e.g., ChatGPT with MCP support) and add the MCP server URL.  
- Authentication occurs during client/server configuration.

## Pricing
The provided content does not include any pricing information for the Azure AI Vision MCP Server or related plans.