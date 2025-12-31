# Signaturely MCP Server

Integration for connecting AI agents and chat clients to Signaturely’s e-signature platform via an MCP (Model Context Protocol) server.

---

## Overview
- **Type:** MCP server integration
- **Category:** Business & commerce – MCP servers
- **Purpose:** Enable AI agents and chat applications to initiate and manage e-signature workflows programmatically using Signaturely.
- **Provider:** Pipedream (integration) with Signaturely (e-signature service)

---

## Features
- **MCP server endpoint**  
  - Static MCP server URL: `https://mcp.pipedream.net/v2`  
  - Same URL works for every client; authentication is handled when adding the server to the application.

- **Signaturely account integration**  
  - Connect a Signaturely account through Pipedream’s configuration flow.  
  - Account verification / status checking ("Checking your account…").

- **Client and chat app support**  
  - Designed to be added to various chat clients that support MCP.  
  - Per-client setup instructions available via the configuration interface.

- **E-signature workflow enablement**  
  - Provides an MCP-accessible interface to Signaturely’s e-signature capabilities (e.g., initiating and managing document signing workflows) for small-business productivity scenarios.  
  - Intended for programmatic control by AI agents and applications.

- **Configuration resources**  
  - Central configuration page for full setup instructions (`/configuration` on Pipedream).  
  - Lists available tools / actions (loaded dynamically in the UI) for interacting with Signaturely via MCP.

---

## Usage
- Copy and use the MCP server URL (`https://mcp.pipedream.net/v2`) when configuring compatible chat clients or AI applications.
- Authenticate with your Signaturely/Pipedream account during server setup in the client.

---

## Pricing
- No explicit pricing details or plans are provided in the available content for the Signaturely MCP Server integration.

---

## Links
- Integration page: https://mcp.pipedream.com/app/signaturely
- Pipedream terms: https://pipedream.com/terms
- Pipedream privacy policy: https://pipedream.com/privacy
- Workday acquisition news (context only): https://newsroom.workday.com/2025-11-19-Workday-Signs-Definitive-Agreement-to-Acquire-Pipedream