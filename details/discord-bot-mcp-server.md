# Discord Bot MCP Server

**Brand:** Pipedream  
**Category:** Messaging MCP Servers  
**Slug:** `discord-bot-mcp-server`

## Description
The Discord Bot MCP Server is a Pipedream-hosted MCP endpoint that connects to the Discord API using a bot in your Discord account. It enables chat clients and workflows to programmatically interact with Discord, including sending messages, responding to events, and managing channels, guild members, and reactions.

## Getting Started
- **MCP Server URL (static for all clients):** `https://mcp.pipedream.net/v2`  
- Authenticate when adding the server to your MCP-compatible application.  
- Connect your Discord bot account in Pipedream, then select your client and follow the configuration instructions.

## Features

### General Capabilities
- Connects to the Discord API using a bot in your Discord account.
- Exposes Discord actions as MCP tools for use in compatible chat clients and workflows.
- Currently provides **22 actions** as tools (subset listed below).

### Messaging & Content
- **Send Message**  
  Send a message to a user or a channel.
- **Send Message With File**  
  Post a message with an attached file.
- **Send Message to Forum Post**  
  Send a message to a Discord forum post.
- **Get Message**  
  Retrieve a specific message in a channel.
- **List Channel Messages**  
  Return messages for a given channel.
- **Post Reaction with Emoji**  
  Add an emoji reaction to a specific message.
- **List Users that Reacted with Emoji**  
  Return a list of users that reacted to a message with a specified emoji.

### Channels & Forums
- **List Channels**  
  Return a list of channels in a guild.
- **Modify Channel**  
  Update a channel’s settings.
- **Rename Channel**  
  Rename a channel to a specified name.
- **List Channel Invites**  
  Return a list of invitees for a channel (guild channels only).

### Guild Members & Users
- **List Guild Members**  
  Return a list of members in a guild.
- **Modify Guild Member**  
  Update attributes of a guild member.
- **Find User**  
  Find an existing user by name.
- **Remove User Role**  
  Remove a selected role from a specified user.

> Note: The app advertises 22 actions in total; only the actions explicitly listed in the source content are included here.

## Pricing
No pricing information is provided in the available content.