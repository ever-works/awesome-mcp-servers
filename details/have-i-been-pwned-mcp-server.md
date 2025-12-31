# Have I Been Pwned MCP Server

An MCP server that integrates with the Have I Been Pwned service, enabling tools and chat-based clients to check whether email addresses or passwords have appeared in known data breaches.

- **Category:** Security Attestation MCP Servers  
- **Brand:** Have I Been Pwned  
- **Source URL:** https://mcp.pipedream.com/app/have_i_been_pwned  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

- **Have I Been Pwned integration**  
  - Connects MCP-compatible clients to the Have I Been Pwned API.  
  - Enables automated checks against known breach databases.

- **Email breach detection**  
  - Check if a specific email address has been exposed in a data breach.

- **Password compromise checks**  
  - Check if a password has appeared in known data breaches (using Have I Been Pwned’s password datasets).

- **Static MCP server endpoint**  
  - Uses a single static URL (`https://mcp.pipedream.net/v2`) that works across supported MCP clients.  
  - Authentication is handled when adding the server to your application.

- **Client-agnostic configuration**  
  - Can be added to various chat or MCP-compatible clients.  
  - Central configuration documentation available via the linked configuration page.

## Usage

- Add the MCP server URL `https://mcp.pipedream.net/v2` to your MCP-compatible or chat-based application.  
- Authenticate as instructed by your client when registering the server.  
- Use provided tools/commands to query whether an email address or password has been involved in a known breach.

## Pricing

- Not specified in the provided content.
