# OCRSpace MCP Server

## Overview
OCRSpace MCP Server exposes the OCR.space Online OCR service through the Model Context Protocol (MCP), allowing AI agents and chat-based tools to convert scanned documents and images (including PDFs) into editable text via Optical Character Recognition.

## Features
- **Optical Character Recognition (OCR)** for text extraction from images and scanned documents.
- **PDF text extraction** to convert PDF files into editable text.
- **Image-based document processing** including photos from smartphones.
- **No-registration OCR.space backend** (the underlying OCR.space service is free to use and does not require registration when used directly).
- **MCP-compatible server endpoint** accessible via a static URL (`https://mcp.pipedream.net/v2`) that can be added to any MCP-capable client.
- **Integration with chat / AI clients** via MCP, enabling AI agents to call OCR operations during conversations.

## Getting Started
- Use the MCP server URL: `https://mcp.pipedream.net/v2`.
- Add this server URL to your MCP-compatible chat client or application and authenticate as required by your client.
- Refer to the provider’s configuration documentation for detailed setup steps.

## Pricing
- The underlying OCR.space Online OCR service is described as **free to use** with **no registration necessary** when accessed directly.
- No additional MCP-specific pricing details are provided in the available content.