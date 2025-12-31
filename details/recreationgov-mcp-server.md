# Recreation.gov MCP Server

An MCP server that connects to the Recreation Information Database (RIDB) at Recreation.gov, providing a single point of access to nationwide recreational opportunity data.

- **Category:** Data Access & Integration MCP Servers  
- **Brand:** recreationgov  
- **Source URL:** https://mcp.pipedream.com/app/recreation_gov  
- **MCP Server URL:** `https://mcp.pipedream.net/v2`

## Overview

The Recreation.gov MCP Server exposes the Recreation Information Database (RIDB) through the MCP protocol, enabling applications and chat clients to query structured data about U.S. recreational opportunities (e.g., recreation areas and campsites) from a central, government open-data source.

## Features

- **RIDB integration**  
  - Connects directly to the Recreation Information Database (RIDB) at Recreation.gov.  
  - Provides unified access to nationwide recreational opportunity data.

- **Static MCP endpoint**  
  - Single static MCP server URL: `https://mcp.pipedream.net/v2`.  
  - Same URL works for all supported clients; authentication occurs when adding the server to an application.

- **Available tools (actions)**  
  1. **Search Recreation Areas**  
     - Searches recreation areas using provided properties / filters.  
     - If no parameters are supplied, returns all recreation areas.  
     - Action documentation: `search-recreation-areas.mjs` (via linked GitHub file).

  2. **Search Campsites**  
     - Searches campsites using a query.  
     - If no query is provided, returns campsites from the beginning of the dataset.  
     - The number of returned campsites is limited to `1000`.  
     - Action documentation: `search-campsites.mjs`.

  3. **Get Recreation Area**  
     - Retrieves details of a specific recreation area (note: page text refers to "campsite" but the action name indicates recreation area details).  
     - Action documentation: `get-recreation-area.mjs`.

- **Client integration**  
  - Designed to be added as an MCP server to compatible chat clients.  
  - Example guidance is provided for ChatGPT (OpenAI) via a setup guide.  
  - Additional configuration instructions are available on a central Configuration page.

- **Account connection (via Pipedream)**  
  - Users can sign in with Pipedream to connect and manage their Recreation.gov-related configuration.  
  - Account connection is used to configure and manage MCP server access.

## Use Cases

- Discovering and listing recreation areas across the United States.  
- Searching for campsites that match specific criteria and queries.  
- Fetching detailed information for a given recreation area to power travel, planning, or outdoor recreation tools and assistants.

## Pricing

- No pricing information is provided in the available content.
