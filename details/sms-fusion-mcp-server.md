# SMS Fusion MCP Server

**Category:** Messaging MCP Servers  
**Brand:** SMS Fusion  
**Slug:** `sms-fusion-mcp-server`

MCP server that connects SMS Fusion’s enterprise SMS platform to MCP-compatible clients, enabling programmatic messaging workflows.

---

## Features

### MCP Server & Connectivity
- Static MCP server endpoint: `https://mcp.pipedream.net/v2`
- Works with multiple MCP-compatible chat clients (e.g., ChatGPT via OpenAI)
- Authentication handled when adding the server to your application
- Usable across all SMS Fusion clients (same base MCP URL for every client)

### Account Integration
- Connect an existing SMS Fusion account
- Select and manage a specific SMS Fusion client/account after sign-in

### Available Tools / Actions
The MCP server currently exposes 3 actions as tools:

1. **Send SMS**  
   - Send an SMS message via SMS Fusion  
   - Uses SMS Fusion’s enterprise-grade SMS infrastructure  
   - Action documented in the Pipedream components repository

2. **Perform HLR Lookup**  
   - Perform an HLR (Home Location Register) lookup on a phone number  
   - Useful for checking number status and reachability before sending messages  
   - Action documented in the Pipedream components repository

3. **Get Balance**  
   - Retrieve the current SMS Fusion account balance  
   - Includes available credit limits  
   - Action documented in the Pipedream components repository

### Documentation & Configuration
- Configuration and usage instructions available via Pipedream’s **Configuration** page
- Additional technical details for each action available in the linked GitHub component files

---

## Pricing

No pricing information is provided in the available content for:
- The SMS Fusion MCP Server usage, or
- SMS Fusion SMS / HLR / balance services.

Pricing must be obtained directly from SMS Fusion or Pipedream’s official resources.