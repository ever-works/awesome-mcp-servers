# Omentir

Omentir is an open-source AI sales workspace for LinkedIn. Its hosted MCP server lets an AI agent find and score LinkedIn prospects, draft outreach, run human-paced campaigns, and answer replies.

## Features

- Read workspace context, product profile, and remaining send allowance.
- Create, update, pause, resume, and delete lead-finding and outreach agents.
- List, inspect, export, and import leads (CSV), and manage lead groups.
- See scheduled actions, activity, stats, conversations, and the inbox.
- Reply to leads and chats, and stop outreach for a lead.

Sends are human-paced with daily limits. The agent cannot create an Omentir account, change billing, connect LinkedIn, or mint API keys, and it never sees the user's LinkedIn password.

## Connection

- **Endpoint:** https://omentir.com/api/agent/v1/mcp
- **Transport:** Streamable HTTP
- **Authentication:** OAuth 2.1 with dynamic client registration and PKCE. API keys from https://omentir.com/api-keys also work as a Bearer token.
- **Official MCP Registry name:** io.github.vanshyadav1408/omentir
- **Website:** https://omentir.com
- **Setup instructions:** https://omentir.com/integrations/mcp
- **Source:** https://github.com/vanshyadav1408/Omentir (MIT, self-hostable with Docker)
- **Pricing:** Pro $49/month hosted; free to self-host.
