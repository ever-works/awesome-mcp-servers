# LiveKit MCP Server

**Description**  
MCP Server for LiveKit that enables real-time audio and video transport between LLMs and users within MCP workflows. Provided via Pipedream as a static MCP endpoint that can be added to compatible chat or MCP clients.

**Category**  
- Messaging MCP Servers

**Tags**  
- Audio-video  
- Real-time  
- Streaming

**Integration & Configuration**  
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
- URL is added as an MCP server in the client; authentication occurs when adding/configuring the server in the application.  
- Requires connecting a LiveKit account within Pipedream.  
- Usable from multiple MCP / chat clients (client-specific setup documented via the configuration page on Pipedream).

## Features

### Real-time Audio & Video for LLM Workflows
- Transports audio and video streams between users and LLMs in real time.  
- Designed for building “realtime AI” experiences (e.g., conversational agents with live media).

### Room & Participant Management Tools (MCP Actions)
The MCP server exposes six LiveKit management actions as tools:

1. **Create Room**  
   - Create a new LiveKit room.  
   - Parameters (from LiveKit docs via linked component) typically include room name and configuration options.

2. **List Rooms**  
   - List all existing rooms in LiveKit.  
   - Allows LLMs or workflows to inspect current active or configured rooms.

3. **Delete Room**  
   - Delete a specified LiveKit room.  
   - Useful for cleanup and lifecycle management in automated workflows.

4. **Generate Access Token**  
   - Generate an access token that allows a participant to join a specific LiveKit room.  
   - Intended to be used by MCP clients / LLMs to onboard users or agents dynamically.

5. **Remove Participants**  
   - Remove one or more specific participants from a LiveKit room.  
   - Supports automated moderation or flow control in live sessions.

6. **Create Ingress From URL**  
   - Create a new ingress in LiveKit from a given URL.  
   - Enables ingesting an external media stream (e.g., from a source URL) into a LiveKit room.

### MCP & Client Compatibility
- Exposed as a standard MCP server, so any MCP-compatible client can integrate with it using the provided URL.  
- Actions are available as tools that LLMs can call during conversations or workflows.

## Pricing

- No pricing information is provided in the available content. Users should refer to Pipedream and LiveKit official documentation or dashboards for current pricing details.