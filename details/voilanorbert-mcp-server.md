# VoilaNorbert MCP Server

## Overview
The VoilaNorbert MCP Server is an MCP-compatible integration that connects VoilaNorbert’s lead generation and corporate email discovery capabilities to chat-based or MCP-enabled applications via a static server URL.

- **Category:** Business & Commerce – MCP Servers  
- **Primary function:** Lead generation, prospecting, and corporate email discovery  
- **MCP server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL (`https://mcp.pipedream.net/v2`) usable across clients.
- Authentication handled when adding the server to your client/application.
- Can be added to multiple MCP-compatible chat clients and tools.

### Available Tools / Actions
There are 3 main actions exposed as tools through this MCP server:

#### 1. Verify Email
- Verifies a provided list of email addresses.
- Uses VoilaNorbert’s verification service to check email validity.
- If the linked VoilaNorbert account has insufficient Verify API balance, the service attempts to auto-refill by charging the account’s stored billing method.
- If auto-refill fails due to billing issues, returns HTTP status code **402**.

#### 2. Start Contact Search
- Initiates an email search based on:
  - Full name, and
  - Domain or company name.
- Returns search results for likely corporate email addresses associated with the provided person and organization.
- If the account lacks sufficient credits, returns HTTP status code **402**.
- Validates the domain:
  - If the domain cannot be located or is invalid, may return HTTP status code **400** for that domain.

#### 3. Find Contact
- Retrieves a specific contact’s information.
- Response structure:
  - `email` field is either:
    - `null` if no email is found, or
    - An object containing at least:
      - `email` (email string)
      - `score` (confidence/quality score for the email)
- Designed to fetch a single, targeted contact record.

## Use Cases
- Integrate corporate email discovery directly into MCP-compatible chat or automation tools.
- Automate lead generation workflows using name + domain/company to find emails.
- Programmatically verify existing email lists for deliverability and validity.
- Pull detailed contact data (email plus score) for sales and prospecting pipelines.

## Pricing
Pricing or plan details are not provided in the available content. Use of email verification and contact search depends on the VoilaNorbert account’s credits and billing configuration; insufficient balance or failed charges result in HTTP 402 responses.