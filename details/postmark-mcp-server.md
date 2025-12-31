# Postmark MCP Server

## Overview
Postmark MCP Server is a Model Context Protocol (MCP) server integration that lets AI agents and MCP-compatible clients interact programmatically with Postmark’s transactional and marketing email platform. It exposes Postmark operations (such as sending emails, managing sender signatures, and verifying DNS/authentication) as tools that can be invoked from supported chat or agent environments.

- **Category:** Messaging MCP Servers  
- **Provider / Brand:** Postmark  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

---

## Features

### MCP Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across compatible clients.
- Authentication handled when adding the server to your MCP-capable application.
- Works with multiple chat/agent clients via the Model Context Protocol.
- Central configuration via a shared configuration page (referenced as “Configuration page”).

### Available Tools (Actions)
The server exposes Postmark operations as tools (24 actions total are available; the following are explicitly listed):

#### DNS & Authentication Management
- **Verify Return-Path DNS**  
  Verify the Return-Path DNS record for a specified domain to confirm correct configuration for bounce handling and deliverability.

- **Verify DKIM**  
  Verify DKIM keys for a specified domain to ensure authenticated email signing.

- **Rotate DKIM Keys**  
  - Create a new DKIM key to replace the current one.  
  - New DNS entries are provided via `DKIMPendingHost` and `DKIMPendingTextValue`.  
  - After DNS verification, values migrate to `DKIMTextValue` / `DKIMPendingTextValue`.  
  - Postmark begins signing emails with the new DKIM key once verification is complete.

#### Sender Signatures & Domains
- **Update Sender Signature**  
  Create a new sender signature or update an existing one associated with your account.

- **Resend Confirmation**  
  Resend a confirmation email for a specific sender signature.

- **List Sender Signatures**  
  Retrieve a list of sender signatures with brief details associated with your account.

- **List Domains**  
  Get a list of domains with an overview of domain details and authentication status.

#### Email Sending
- **Send Single Email**  
  Send a single transactional or marketing email via Postmark.

- **Send Email With Template**  
  Send a single email using a predefined Postmark template.

- **Send Batch With Templates**  
  Send a batch of emails, each using a template (e.g., personalized template-based bulk sending).

#### Analytics & Deliverability Metrics
- **Get Tracked Email Counts**  
  Retrieve total counts of emails sent with open tracking or link tracking enabled.

- **Get Spam Complaints**  
  Retrieve counts of recipients who have marked your email as spam.

> Note: The page states there are 24 total actions available as tools; only the above subset is explicitly listed in the provided content.

---

## Pricing
No pricing information for the Postmark MCP Server integration is provided in the supplied content.

---

## Tags
- email  
- transactional-email  
- deliverability