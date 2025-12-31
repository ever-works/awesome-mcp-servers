# Zep MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** Zep

Zep MCP Server integrates Zep’s AI memory layer with the Model Context Protocol, enabling agents and AI assistants to use persistent memory and stored knowledge to handle complex tasks.

---

## Description
Zep MCP Server provides a foundational memory layer for AI agents via the Model Context Protocol. By connecting your Zep account to compatible MCP clients, agents can create and manage sessions, users, threads, and associated memories, allowing them to retain context over time and work with historical conversation data.

The server is exposed through a static MCP URL:

- **MCP Server URL:** `https://mcp.pipedream.net/v2`

This URL is added to MCP-compatible chat or agent applications, where you then authenticate with Zep to start using the tools.

---

## Features

### MCP Integration
- Provides a static MCP-compatible server endpoint (`https://mcp.pipedream.net/v2`).
- Can be added to various MCP-capable chat or agent clients.
- Authentication is handled when adding the server to an application.

### Zep Memory & Session Management Tools
The server exposes **6 actions as tools** for agents:

1. **Update Session**  
   - Updates an existing session in Zep.  
   - Used to modify session metadata or properties as conversations evolve.

2. **Get Threads**  
   - Returns a **paginated list of threads** associated with Zep sessions.  
   - Enables agents to browse and retrieve historical conversation threads or task-related threads.

3. **Get Thread Messages**  
   - Retrieves **messages for a specific thread** by ID.  
   - Allows agents to load detailed conversation history or context for a particular thread.

4. **Create Session**  
   - Creates a **new session** in Zep.  
   - Lets agents establish new long-lived contexts for users, tasks, or workflows.

5. **Add User**  
   - Adds a **user** record in Zep.  
   - Supports associating sessions and memories with specific users.

6. **Add Memory to Session**  
   - Adds **memory** items to an existing session.  
   - Enables persistent storage of knowledge, summaries, or important data points that agents can later retrieve.

### Use Cases (Implied by Functionality)
- Maintaining long-lived conversational context across sessions and threads.
- Storing and retrieving task-relevant knowledge as “memories.”
- Managing multiple users and their associated sessions and histories.

---

## Pricing
Pricing information is not provided in the available content.

---

## Tags
- memory  
- rag  
- ai-assistant

---

## Source
- **Integration page:** https://mcp.pipedream.com/app/zep