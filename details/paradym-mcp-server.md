# Paradym MCP Server

**Category:** Security & Attestation MCP Servers  
**Brand:** Paradym  
**Source:** https://mcp.pipedream.com/app/paradym

## Overview
Paradym MCP Server is an MCP server integration that connects Paradym’s verifiable credentials platform to compatible chat or MCP-enabled clients. It provides a static MCP endpoint and tools for creating and managing credential issuance and verification flows using OpenID4VC and DIDComm.

## Features

### MCP Server Endpoint
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`
- Authentication performed when adding the server to an application
- Works across multiple MCP-compatible chat clients

### Account & Configuration
- Connect a Paradym account to manage credentials and verification flows
- Select client / chat interface during setup
- Central configuration available via a dedicated configuration page (client setup guidance)

### Available Tools (Actions)
The server exposes 4 actions as tools:

1. **Get OpenID4VC Verification Session**
   - Fetches verification session data for a specified session ID
   - Useful for checking status and details of ongoing or completed verifications

2. **Create OpenID4VC Verification Request**
   - Initiates a new verification request based on a selected template
   - Supports template-driven verification flows using OpenID4VC

3. **Create OpenID4VC Credential Offer**
   - Creates an OpenID4VC issuance offer for selected credentials
   - Enables issuing verifiable credentials via OpenID4VC flows

4. **Create DIDComm Issuance Offer**
   - Creates a DIDComm-based issuance offer for selected credentials
   - Supports credential issuance using DIDComm protocols

## Use Cases
- Automating verification flows for verifiable credentials within chat or agent environments
- Issuing credentials via OpenID4VC or DIDComm from an MCP-enabled client
- Retrieving and inspecting verification session status programmatically

## Pricing
No pricing information is provided in the available content.