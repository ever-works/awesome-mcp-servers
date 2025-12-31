# Turkish Airlines MCP Server

**Category:** Business & Commerce MCP Servers  
**Brand:** Turkish Technology  
**Server URL:** `https://mcp.turkishtechlab.com/mcp`  
**Auth:** OAuth 2.1 (OAuth 2.0-based flow for MCP clients)

Turkish Airlines MCP Server is an airline-focused Model Context Protocol (MCP) server that exposes Turkish Airlines’ flight and loyalty services to AI agents and MCP-compatible clients. It enables real-time, bookable flight interactions and personalized travel services through chat-based interfaces.

## Features

### Flight Operations & Travel Management
- Real-time flight status tracking by flight number or route
- Flight search for outbound and inbound journeys
- Flight booking capabilities via AI agents
- Comprehensive booking management:
  - PNR-based lookup
  - E‑ticket support
- Check-in status monitoring
- Baggage allowance information and lookup
- Alternative flight options during delays or disruptions

### Loyalty & Personalized Services
- Miles & Smiles member profile management
- Expiring miles calculation and tracking
- Access to personalized airline promotions and campaigns
- City and destination travel guides with location-specific recommendations
- Personalized travel recommendations for:
  - Individual travelers
  - Frequent flyers
  - Business travelers

### MCP / AI Integration
- Built on Anthropic’s Model Context Protocol (MCP)
- Live, distributable access for AI agents and MCP clients
- Hosts 14 different MCP tools covering major aspects of air travel
- Designed for use with:
  - Claude MCP clients
  - ChatGPT and Claude custom connectors
  - Other MCP-compatible AI agents and applications
- Supports natural language queries such as:
  - “What is the status of flight TK123?”
  - “If there is a delay, what are alternative flights from Istanbul to New York?”
- Real-time data synchronization with Turkish Airlines backend systems

### Target Use Cases
- **Travelers & Passengers**
  - Check real-time flight status
  - Manage bookings and check-in
  - View baggage rules and allowances
  - Receive destination insights and recommendations
- **Frequent Flyers**
  - Track Miles & Smiles balance
  - Monitor expiring miles
  - Discover member promotions and campaigns
- **Business Travelers**
  - Streamlined check-in and booking modification
  - Baggage and disruption management
- **Developers & Businesses**
  - Integrate Turkish Airlines data into AI apps via MCP
  - Build travel management tools using standardized MCP protocols
  - Corporate travel automation and booking workflows

### Security & Architecture
- OAuth 2.1 / OAuth 2.0-based authentication for secure member access
- Member-specific feature exposure based on authenticated identity
- Cloud-based deployment with:
  - Enterprise-level security
  - High availability for global users
  - Scalable, low-latency design
- Simple MCP client configuration using only the server URL, with client-driven auth flow

## Pricing
Pricing information is not provided in the available content.