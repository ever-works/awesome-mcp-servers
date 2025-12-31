## MCP-Geo

**Category:** Data Access & Integration – MCP Servers  
**Brand:** webcoderz  
**License:** MIT  
**Repository:** https://github.com/webcoderz/MCP-Geo

MCP-Geo is an open-source Model Context Protocol (MCP) server that exposes geocoding and reverse geocoding capabilities using GeoPy and multiple location service APIs, allowing MCP-compatible clients (e.g., AI assistants) to resolve addresses, coordinates, and place information.

### Features

- **MCP server implementation**
  - Built on the **fastmcp** framework for creating MCP servers.
  - Designed to plug into MCP-compatible clients (e.g., Claude Desktop) as a geocoding tool provider.

- **Geocoding capabilities**
  - Uses **GeoPy** to interface with various geocoding/location APIs.
  - Forward geocoding: convert human-readable addresses or place names to geographic coordinates (latitude/longitude).
  - Reverse geocoding: convert coordinates to structured address/place information.
  - Built to support “multiple location services APIs” through GeoPy’s provider ecosystem (e.g., OpenStreetMap/Nominatim and others, depending on GeoPy configuration and API keys).

- **MCP tools exposure**
  - Exposes geocoding actions as MCP tools so AI agents can:
    - Call geocoding endpoints programmatically.
    - Request reverse geocoding directly from within an MCP-enabled environment.
  - Tools are defined in `geo.py` and integrated via `fastmcp`.

- **Configuration & environment variables**
  - Supports configuration through environment variables (details are in the repo’s Environment Variables section), typically used for:
    - API keys or credentials for specific geocoding providers.
    - Provider selection and configuration options.

- **Install & runtime requirements**
  - Requires **Python 3.6+**.
  - Depends on:
    - `fastmcp` – MCP server framework.
    - `geopy` – geocoding / reverse geocoding library.
  - Dependencies are declared in `requirements.txt` (and `pyproject.toml` / `uv.lock` for uv-based environments).
  - Supports installation and use:
    - As a tool in **Claude Desktop**.
    - In other MCP-compatible environments (“Elsewhere” option in README).

- **Development & documentation**
  - Includes sections for Development Documentation and Safety Features (see README in repo), describing how to run, extend, and safely use the MCP tools.

### Pricing

- MCP-Geo is an open-source project licensed under the **MIT License** and can be used at no cost.  
- Any costs incurred would be from third-party geocoding providers used via GeoPy (API usage, rate limits, etc.), which are external to this project and depend on your chosen providers’ pricing.
