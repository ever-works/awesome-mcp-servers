# FraudLabs Pro MCP Server

**Category:** Security / Attestation MCP Server  
**Brand:** FraudLabs Pro  
**Slug:** `fraudlabs-pro-mcp-server`

## Overview
FraudLabs Pro MCP Server integrates the FraudLabs Pro service into MCP to enable fraud screening and risk analysis for online transactions. It is designed to help protect e‑commerce stores from payment fraud (CNP fraud) across transactions using credit cards, PayPal, and similar payment methods.

The MCP server is exposed via a static URL:

```text
https://mcp.pipedream.net/v2
```

## Features
- **Fraud screening for online transactions**
  - Screens sales orders for potential payment fraud (card‑not‑present / CNP fraud).
  - Supports common online payment methods such as credit cards and PayPal.
- **MCP server integration**
  - Single static MCP server URL that works for all clients.
  - Authentication handled when adding the server to your application.
- **OTP verification tools (2 actions exposed as tools)**
  - **Send SMS Verification**
    - Sends an SMS containing a verification code and optional custom message.
    - Used for authentication and additional verification of users.
    - Requires a valid FraudLabs Pro API key.
    - Requires sufficient SMS credit balance to send verification messages.
  - **Get Verification Result**
    - Verifies whether a one‑time password (OTP), previously sent via the Send SMS Verification API, is valid.
    - Returns a structured result as defined in FraudLabs Pro’s documentation.
- **Configuration via MCP‑compatible clients**
  - Can be added to compatible chat or MCP clients as a server endpoint.
  - Further configuration details available on the platform’s configuration page (selection of client, account connection, etc.).

## Pricing
The provided content does not include any pricing details or plan information for FraudLabs Pro MCP Server or related SMS/OTP services. Pricing and SMS credits appear to be managed via FraudLabs Pro’s own plans (e.g., Micro Plan) and must be obtained from FraudLabs Pro directly.