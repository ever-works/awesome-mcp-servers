## Trello MCP Server

**Category:** Project Management MCP Servers  
**Source:** https://mcp.pipedream.com/app/trello

Trello MCP Server is an MCP-compatible integration that connects Trello with MCP-enabled clients (such as ChatGPT), allowing you to manage Trello boards, cards, lists, and related objects directly from your MCP client.

---

### Connection & Configuration
- Static MCP server URL for all clients:
  - `https://mcp.pipedream.net/v2`
- Authentication occurs when adding the server to your MCP-compatible application.
- Client-specific setup instructions available (e.g., ChatGPT / OpenAI) via the configuration guide.

---

### Features

#### General
- MCP server interface for Trello’s REST API.
- Enables Trello project management operations from within MCP-compatible chat or tooling environments.
- Works with a single static server URL and per-client authentication.

#### Available Tools (Actions)
The server exposes **28 Trello actions** as MCP tools. The page lists the following explicitly:

1. **Update Card**  
   - Update an existing Trello card.

2. **Search Members**  
   - Search for Trello members.

3. **Search Checklists**  
   - Find a checklist on a specific board or card by name.

4. **Search Cards**  
   - Search for cards that match a specified query.

5. **Search Boards**  
   - Search for boards that match a specified query.

6. **Rename List**  
   - Rename an existing list.

7. **Remove Card Label**  
   - Remove a label from a card.

8. **Move Card to List**  
   - Move a card to a specified board/list pair.

9. **Get List**  
   - Retrieve information about a list.

10. **Get Cards On A Board**  
    - Get all open cards on a board.

11. **Get Cards In A List**  
    - List all cards in a list.

12. **Get Card**  
    - Retrieve a card by its ID.

> Note: The page states that there are 28 actions available as tools; only the above subset is shown in the provided content.

---

### Pricing
No pricing information is provided in the supplied content.