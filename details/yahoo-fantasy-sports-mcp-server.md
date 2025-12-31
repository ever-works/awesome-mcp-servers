# Yahoo! Fantasy Sports MCP Server

**Category:** Game Server MCP Implementations  
**Brand:** Yahoo  
**Slug:** `yahoo-fantasy-sports-mcp-server`

An MCP server that exposes Yahoo! Fantasy Sports functionality to MCP-compatible clients, enabling fantasy league and team interactions through a unified tools interface.

![Yahoo! Fantasy Sports logo](https://s.yimg.com/rz/p/yahoo_sports_en-US_s_f_pw_351X40_sports.png)

## Features

- Connects MCP clients to Yahoo! Fantasy Sports data and actions.  
- Supports creating or joining NFL fantasy leagues.  
- Enables management of fantasy teams (e.g., roster changes, lineup management) via MCP-compatible chat or agent clients.  
- Provides access to live scoring information for NFL fantasy matchups.  
- Exposes player and team stats relevant to Yahoo! Fantasy Sports.  
- Surfaces scouting-style information and reports (where available via Yahoo! Fantasy Sports).  
- Provides access to news related to fantasy-relevant players and teams.  
- Can relay expert advice content from Yahoo! Fantasy Sports where available.  
- Uses a single static MCP server URL for all clients: `https://mcp.pipedream.net/v2`.  
- Designed to be added to multiple MCP-enabled chat clients via configuration.

## Integration Details

- **MCP Server URL:** `https://mcp.pipedream.net/v2`  
- **Auth:** Handled when adding the server to the client (per-client authentication flow).  
- **Client compatibility:** Any MCP-capable client that supports configuring a custom MCP server URL.

## Images

- ![Yahoo Fantasy Image 1](https://s.yimg.com/uu/api/res/1.2/7QZ9FOOyyFllwU5CpRCh5w--~B/aD0yMDAwO3c9MzAwMDthcHBpZD15dGFjaHlvbg--/https://media.zenfs.com/en-US/homerun/yahoo_sports_842/8a3969ab1c9c7e02ba9a75c5d8c4a2e4)
- ![Yahoo Fantasy Image 2](https://s.yimg.com/cv/apiv2/default/mlb/2023/05/Generic_Yahoo_Fantasy_Baseball.png)

## Tags

- sports  
- fantasy-sports  
- game-data

## Pricing

- Not specified in the provided content.