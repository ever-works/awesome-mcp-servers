# DC Hub

Live data-center site-selection data for AI agents, including the daily Data Center Power Index (DCPI) that scores grid power in 300+ markets.

## Basic Info

- **Name:** DC Hub
- **Category:** Data Analysis & Exploration MCP Servers
- **Source URL:** https://github.com/azmartone67/dchub-mcp-server
- **MCP Endpoint:** `https://dchub.cloud/mcp`
- **Tags:** `infrastructure`, `energy`, `geospatial`, `remote`

## Features

- Data Center Power Index (DCPI): a daily score of grid power availability across 300+ markets.
- Power grid, energy, interconnection queue, fiber and gas data.
- Global facility map and tracked data-center M&A deals.

## Setup

- Claude Code: `claude mcp add dchub --transport http https://dchub.cloud/mcp`
- Local alternative: `npx -y dchub-mcp-server`
