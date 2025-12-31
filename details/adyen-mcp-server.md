## Adyen MCP Server

**Category:** Business & Commerce · MCP Servers  
**Brand:** Adyen  
**URL:** https://mcp.pipedream.com/app/adyen

### Description
Adyen MCP Server is an MCP integration for Adyen’s end-to-end payments, data, and financial management platform. It exposes Adyen payment operations as tools that MCP-compatible agents and applications can call programmatically via a static MCP server URL.

### Features
- **MCP server endpoint**  
  - Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
  - Authentication handled when adding the server to an MCP-compatible application.

- **Adyen account integration**  
  - Connect an Adyen account within the Pipedream environment.  
  - Configure client-specific access to Adyen payment functionality.

- **Payment operations exposed as tools (5 actions)**  
  - **Create Payment**  
    - Create a payment for a shopper using Adyen’s payments API.  
  - **Submit Additional Payment Details**  
    - Submit required additional details for an existing payment (e.g., 3DS or other follow-up data) to continue or finalize processing.  
  - **Capture Payment**  
    - Capture an authorized payment.  
    - Supports delayed capture scenarios (e.g., verify order before capturing funds).  
  - **Refund Payment**  
    - Refund a captured payment.  
  - **Cancel Payment**  
    - Cancel a payment that has not yet been captured.

- **Client-agnostic setup**  
  - Same MCP server URL usable across different chat or agent clients.  
  - Configuration instructions available per client type via the configuration page.

### Pricing
No pricing information is provided in the available content.