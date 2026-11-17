# SkyAccess MCP Server

Search 5,000+ live empty leg flights, get charter price estimates and booking links. No account or API key.

## Basic Info

- **Name:** SkyAccess MCP Server
- **Category:** Travel Transportation
- **Brand:** SkyAccess
- **Website:** https://skyaccess.com
- **Source URL:** https://github.com/sky-access/skyaccess-mcp
- **MCP Endpoint:** `https://mcp.skyaccess.com/mcp`
- **License:** MIT
- **Tags:** `travel`, `aviation`, `flights`, `booking`, `transportation`, `remote`

## Features

- `search_empty_legs`: search 5,000+ live private jet empty leg flights by origin, destination, date range and passenger count.
- `get_flight`: look up a single empty leg flight by its flight id.
- `booking_handoff`: return the SkyAccess booking page link for a flight so the traveler can review and book it.
- `get_charter_estimate`: return an indicative price range for a private charter route.
- `request_booking`: send a charter booking request to the SkyAccess team.
- Flights from 900+ FAA Part 135 (and international equivalent) certified charter operators, typically 25 to 75% below a comparable full charter.
- Official MCP Registry listing for `com.skyaccess/skyaccess`.

## Setup & Configuration

- Add `https://mcp.skyaccess.com/mcp` as a remote MCP server (streamable HTTP) in an MCP-compatible client.
- No account, OAuth flow or API key is required.
- Privacy: https://skyaccess.com/privacy#connector
- Terms: https://skyaccess.com/terms
