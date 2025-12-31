# Symbl.ai MCP Server

AI platform for analyzing open‑domain human‑to‑human conversations, exposed as an MCP server usable from compatible MCP clients and agents.

- **Category:** AI Integration – MCP Servers  
- **Brand:** Symbl.ai  
- **Slug:** `symblai-mcp-server`  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Description
The Symbl.ai MCP Server connects MCP-compatible chat and agent clients to Symbl.ai’s conversation intelligence APIs. It enables ingestion and analysis of audio and video conversations, along with retrieval of transcripts, topics, trackers, questions, summaries, and other derived insights.

## Features

### MCP Integration
- Static MCP server endpoint (`https://mcp.pipedream.net/v2`) usable across supported MCP clients.  
- Authentication handled when adding the server to each client/application.  
- Configuration flow guided per client via a configuration page.

### Conversation Input & Processing
- **Submit Video URL**  
  - Send a video file by URL for processing and analysis.
- **Submit Audio URL**  
  - Send an audio file by URL for processing and analysis.
- **Submit Video Summary User Interface**  
  - Provides a Video Summary UI to interact with conversation elements (transcripts, questions, follow‑ups, action items, etc.) derived from video conversations.
- **Submit Trackers and Analytics Summary User Interface**  
  - Provides a Trackers & Analytics UI to interact with Symbl elements (transcripts, questions, follow‑ups, action items, etc.) from audio conversations.

### Conversation Management
- **Update Conversation**  
  - Update an existing Conversation object with metadata or other information.
- **Update Member**  
  - Update an existing Conversation Member object.
- **Update Speaker Events**  
  - Update Speaker Events associated with a conversation.

### Output, Transcription & Analytics
- **Create Formatted Transcript**  
  - Generate a formatted transcript from a conversation.
- **Get Speech to Text**  
  - Retrieve a list of all messages in a conversation (speech‑to‑text output).
- **Get Topics**  
  - Retrieve a list of topics automatically generated from the conversation.
- **Get Trackers**  
  - Retrieve a list of detected trackers (pattern- or intent-like signals) in the conversation.
- **Get Summary**  
  - Retrieve a summary of important contextual messages and content in a conversation.

### Tooling Scope
- 22 actions are exposed as tools through the MCP server (only a subset is listed explicitly above; the remaining actions follow similar patterns for working with Symbl conversation intelligence resources).

## Pricing
Pricing details are not provided in the available content. Use of this MCP server may depend on Symbl.ai and/or Pipedream/Workday account and billing terms; refer to their official documentation for pricing information.