# Google Vertex AI MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** Google Cloud Vertex AI  
**Source:** https://mcp.pipedream.com/app/google_vertex_ai

## Overview
The Google Vertex AI MCP Server exposes Google Vertex AI’s generative AI capabilities and foundation models through the Model Context Protocol (MCP). It lets MCP-compatible clients call Vertex AI tools for text analysis, classification, sentiment analysis, and multimodal (image/video) analysis and generation.

## Features

- **MCP server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Single URL usable across supported MCP clients  
  - Authentication handled when adding the server to each application/client

- **Vertex AI integration**  
  - Connects MCP clients to Google Vertex AI’s generative AI and foundation models  
  - Uses Vertex AI’s unified AI platform for text, image, and video workloads

- **Available tools (actions)**  
  1. **Generate Video from Text**  
     - Generates video content from a text prompt  
     - Uses Google Vertex AI Veo models for video generation
  
  2. **Generate Video from Image**  
     - Generates a video from an input image  
     - Optional text prompt to guide video generation  
     - Uses Google Vertex AI Veo models
  
  3. **Classify Text**  
     - Groups or assigns a provided text into predefined categories  
     - Suitable for content tagging, topic classification, or routing
  
  4. **Analyze Text Sentiment**  
     - Analyzes text for underlying sentiment (e.g., positive/negative/neutral)  
     - Useful for feedback, reviews, and opinion analysis
  
  5. **Analyze Image/Video**  
     - Examines an image or video according to provided instructions  
     - Returns structured analysis findings about the visual content

- **Client compatibility**  
  - Designed for use with MCP-compatible chat and AI clients  
  - Can be added to various applications via the shared MCP server URL

## Pricing
No pricing information is provided in the available content. Pricing for underlying Google Vertex AI usage and any Pipedream-related costs must be obtained from their respective official pricing pages.