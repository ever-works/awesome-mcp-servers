# Slack Bot MCP Server

## Overview
Slack Bot MCP Server is an MCP (Model Context Protocol) server that connects to Slack using a bot user. It enables programmatic interactions and automations in Slack from compatible MCP clients via a single static server URL.

- **Category:** Messaging MCP Servers  
- **Brand:** Slack / Pipedream  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Features

### MCP Integration
- Static MCP server URL usable across all compatible clients.
- Authentication handled when adding the server to your MCP-enabled application.
- Works with a dedicated Slack bot user for actions and automations.

### Messaging & Threads
- **Send Message:** Send a message as the bot to a user, group, private channel, or public channel.
- **Send Message (Advanced):** Send messages with advanced configuration options (e.g., additional Slack API parameters via postMessage / scheduleMessage).
- **Send a Large Message (3000+ characters):** Send long-form messages that exceed Slack’s standard text length in a single action.
- **Reply to a Message Thread:** Post threaded replies to existing messages, keeping conversations organized.
- **Update Message:** Edit an existing message previously sent by the bot.

### Channel & Group Management
- **Set Channel Topic:** Programmatically update the topic of a specific channel.
- **Set Channel Description:** Change the description / purpose of a channel.
- **List Members in Channel:** Retrieve members of a specific channel.
- **Update Groups Members:** Update the list of users in a Slack User Group.
- **List Group Members:** List all users associated with a specific User Group.

### Users & Files
- **List Users:** Return a list of all users in a Slack workspace accessible to the bot.
- **List Files:** Return a list of files within the team that the bot can access.

### Conversations & Threads
- **List Replies:** Retrieve an entire message thread (replies) for a given conversation.

> Note: The server exposes a total of **24 actions** as tools; only those explicitly listed in the available content are detailed above.

## Configuration
- Connect your Slack account and configure the "Bot for Slack" integration in Pipedream.
- Copy the MCP server URL (`https://mcp.pipedream.net/v2`).
- Add the server to your MCP-compatible client and authenticate when prompted.
- Additional client-specific setup details are available on the provider’s configuration page.

## Pricing
- No explicit pricing information is provided in the available content. Use of this MCP server may depend on Pipedream and Slack plan terms.