## BTCPay Server MCP Server

### Description
MCP Server integration for BTCPay Server, the open‑source, self‑hosted Bitcoin payment processor. This integration allows AI tools and MCP‑compatible clients to interact with BTCPay Server to manage Bitcoin payments without intermediaries, using the Model Context Protocol.

- Product type: MCP server / integration
- Main purpose: Enable AI and chat clients to work with BTCPay Server for Bitcoin payment processing
- Deployment: Accessed via a static MCP endpoint URL; BTCPay Server itself is self‑hosted and open source

### Features
- **MCP-compatible endpoint**: Uses a single static MCP server URL that works across clients:
  - `https://mcp.pipedream.net/v2`
- **Client-agnostic integration**: Designed to be added to any MCP‑capable chat client or application.
- **Authentication at client setup**: Authentication occurs when adding the server to your application, rather than through client‑specific URLs.
- **Bitcoin payment processing via BTCPay Server**:
  - Integrates with BTCPay Server, a self‑hosted Bitcoin payment processor.
  - Supports accepting Bitcoin payments with no intermediary.
  - Leverages an open‑source stack for payment operations.
- **Self-sovereign setup**: Built to work with self‑hosted BTCPay Server instances, aligning with self‑custody / self‑sovereign usage.
- **Configuration documentation**: A dedicated configuration page (linked from the app) explains how to add and configure the server for different clients.

### Category
- Blockchain & Crypto MCP Servers

### Tags
- Bitcoin
- Payments
- Open-source

### Pricing
- Not specified in the provided content.

### Links
- MCP server URL: `https://mcp.pipedream.net/v2`
- App page: https://mcp.pipedream.com/app/btcpay_server
- Configuration docs: (via the "Configuration" link on the app page)
- Provider: Pipedream Connect (pipedream.com)