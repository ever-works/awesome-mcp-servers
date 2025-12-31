# Dodo Payments MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Dodo Payments  
**Website:** https://docs.dodopayments.com/developer-resources/mcp-server

![Dodo Payments MCP Server](https://dodopayments.com/dodo-dashboard.png)

## Description
The Dodo Payments MCP Server exposes Dodo Payments’ payment and billing capabilities to AI assistants via the Model Context Protocol (MCP). It allows MCP-compatible clients (such as Claude and Cursor) to securely perform payment operations, subscription management, and customer interactions by executing TypeScript code against the Dodo Payments SDK in a sandboxed environment.

## Features

### MCP Integration
- Implements the Model Context Protocol (MCP) for structured, secure access to Dodo Payments APIs.  
- Compatible with AI assistants and tools that support MCP (e.g., Claude, Cursor).  
- Uses SSE-based MCP connections for communication.

### Code Mode Architecture
- Built with Stainless and uses a **Code Mode** architecture.  
- AI agents write and execute TypeScript code against the Dodo Payments SDK.  
- Execution occurs in an isolated sandbox environment.  
- No web or filesystem access from the sandbox for enhanced security.  
- Designed for deterministic, repeatable multi-step payment operations.

### Tools Exposed to AI Agents
- **Docs Search Tool**  
  - Query Dodo Payments API and SDK documentation.  
  - Discover available operations, parameters, and usage patterns.

- **Code Execution Tool**  
  - Run TypeScript code snippets using the Dodo Payments SDK.  
  - Perform end-to-end workflows (e.g., create payment, issue refund, update subscription).  
  - Encapsulate complex logic in code rather than single API calls.

### Key Capabilities
- **Payment Operations**  
  - Create payments.  
  - Retrieve payment details.  
  - Manage payments and refunds.

- **Subscription Management**  
  - Handle recurring billing.  
  - Process upgrades and downgrades.  
  - Manage cancellations.

- **Customer Administration**  
  - Manage customer records and data.  
  - Manage customer portal access.

- **Product Catalog Management**  
  - Create and update products.  
  - Configure pricing.  
  - Manage discounts.

- **License Management**  
  - Activate software licenses.  
  - Validate existing licenses.  
  - Manage license lifecycle.

- **Usage-Based Billing**  
  - Track metered usage.  
  - Bill customers based on recorded usage.

## Pricing
Pricing details for the Dodo Payments MCP Server are not specified in the provided content. Refer to the main Dodo Payments site or documentation for current pricing information.