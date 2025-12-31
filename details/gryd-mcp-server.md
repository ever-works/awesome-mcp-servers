# Gryd MCP Server

**Description**  
Gryd MCP Server is an MCP-compatible integration that connects to Gryd’s real-time vehicle data platform, allowing applications to access telematics and mobility data through a standardized interface.

**Category**  
Data Access & Integration · MCP Servers

**Key Capabilities**
- Standard MCP server endpoint usable across clients
- Integration with Gryd’s real-time vehicle data platform
- Access to vehicle-related regulatory and registration data (ULEZ, MOT, DVLA)
- Authentication handled when adding the server to an MCP-compatible application

**MCP Server URL**
- Static server URL (used for all clients):
  - `https://mcp.pipedream.net/v2`

**Features**
- **Unified MCP Interface**  
  - Single static MCP server URL that works for every client
  - Server added once to an application; authentication performed during setup

- **Vehicle Data Retrieval Tools (Actions)**  
  The server exposes 4 actions as tools against the Gryd API:
  - **Get Vehicle ULEZ Data**  
    - Fetches Ultra Low Emission Zone (ULEZ) data for a specific vehicle from the Gryd API.
  - **Get Vehicle MOT Data**  
    - Fetches MOT (roadworthiness test) data for a specific vehicle from the Gryd API.
  - **Get Vehicle DVLA Data**  
    - Fetches DVLA-related data (e.g., UK vehicle registration authority data) for a specific vehicle from the Gryd API.
  - **Get Vehicle Data**  
    - Fetches general data for a specific vehicle from the Gryd API.

- **Client-Agnostic Usage**  
  - Designed to be added to various chat or MCP-compatible clients
  - Configuration guidance available via a separate configuration page (not client-specific here)

**Integration & Configuration**
- Requires a Gryd account connection via the Pipedream interface
- After sign-in, users select their Gryd client and configure access
- Server URL remains constant; client setup and authentication occur when adding the server to the target app

**Pricing**
- No pricing information is provided in the available content.
