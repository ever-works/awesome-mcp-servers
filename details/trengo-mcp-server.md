# Trengo MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Trengo  
**Source:** https://mcp.pipedream.com/app/trengo

An MCP server that connects Trengo’s customer service and help desk platform to MCP-compatible AI agents, enabling omnichannel messaging and support workflows through standardized tools.

---

## Features

### MCP Server & Connection
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.
- Connects a Trengo account to MCP-compatible applications.
- Authentication handled when adding the server to the client application.
- Usable across different chat clients that support MCP.

### Available Tools (Actions)
The server exposes Trengo operations as tools (23 actions in total, including):

#### Messaging & Communication
- **Send A Message**  
  - Send a message or email without needing to manually manage contacts or tickets.
- **Send A Ticket Message**  
  - Send a message to an existing ticket.
- **Send A Team Chat Message**  
  - Send a message as a bot in Trengo Team Chat.
- **Send A WhatsApp Message Template**  
  - Send a WhatsApp message using pre-defined templates.

#### Voice & Call Logging
- **Log A Voice Call**  
  - Log a phone call coming from external VoIP applications into Trengo.

#### Tickets & Messages
- **List Tickets**  
  - List tickets according to specified filters/criteria.
- **List Messages**  
  - List messages associated with a given ticket.
- **Get Message**  
  - Retrieve a specific message by its ID.

#### Labels
- **List Labels**  
  - List all labels in the Trengo workspace.
- **Get Label**  
  - Retrieve a label by its ID.

#### Help Center & Knowledge Base
- **List Help Centers**  
  - List all help centers in the Trengo account.
- **Get Help Center**  
  - Retrieve a specific help center (partial info from truncated content).
- **List Articles**  
  - List articles from a help center based on specified criteria.
- **List All Categories**  
  - List all categories within a help center.
- **List All Blocks**  
  - List all blocks within a help center.

#### Quick Replies
- **List All Quick Replies**  
  - List all predefined quick replies available in Trengo.

> Note: The page states there are 23 actions available; only those explicitly visible in the provided content are listed above.

---

## Use Cases
- Integrate Trengo customer service workflows with AI chat agents via MCP.
- Automate ticket messaging, team chat updates, and WhatsApp template sends from AI-driven workflows.
- Have AI agents read from and write to Trengo tickets, labels, and help center content.
- Log external VoIP calls into Trengo through AI- or automation-triggered flows.

---

## Configuration
- Copy the static MCP server URL (`https://mcp.pipedream.net/v2`).
- Add the server to an MCP-compatible application or chat client.
- Authenticate with a Trengo account during server setup in the client.
- Further setup details are available on the platform’s configuration page (not reproduced here).

---

## Pricing
- No pricing information is provided in the available content.