# Paystack MCP Server

**Description:**  
An MCP Server integration for Paystack that lets MCP‑compatible agents and chat clients interact with Paystack’s payment processing APIs via Pipedream.

**Category:** Business & Commerce MCP Servers  
**Brand:** Paystack  
**Source URL:** https://mcp.pipedream.com/app/paystack

---

## Features

### MCP Server Integration
- Static MCP server endpoint: `https://mcp.pipedream.net/v2` (shared across clients).
- Can be added to compatible chat clients / MCP applications to enable Paystack actions.
- Authentication is handled when adding the server to your application.

### Available Tools (Actions)
The server exposes 6 Paystack-related actions as tools:

1. **Verify Transaction**  
   - Confirms the status of a specific transaction.  
   - Useful for checking whether a transaction succeeded, failed, or is pending.

2. **List Transactions**  
   - Retrieves a list of transactions carried out on your Paystack integration.  
   - Can be used to review recent payments, reconciliations, and histories.

3. **Initialize Transaction**  
   - Starts a new transaction on Paystack.  
   - Typically used to create a payment session / link before customer checkout.

4. **Fetch Transaction**  
   - Fetches details of a single transaction by identifier.  
   - Provides granular information about a specific payment event.

5. **Export Transactions**  
   - Exports transactions data from Paystack.  
   - Intended for reporting, analytics, or external reconciliation workflows.

6. **Charge Authorization**  
   - Charges an existing reusable authorization (e.g., a saved card token).  
   - Enables subsequent charges without requiring full payment details again.

---

## Technical Notes
- Requires a Paystack account and API credentials to use the actions.
- Configuration is handled through Pipedream’s MCP configuration flow.

---

## Pricing
No specific pricing information for the Paystack MCP Server integration is provided in the available content. Pricing may depend on Pipedream and Paystack’s own billing models.