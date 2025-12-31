# Map Traveler MCP

## Overview
Map Traveler MCP is a Model Context Protocol (MCP) server that connects LLMs with multiple location and media services. It enables virtual location simulations, map exploration, and image generation by integrating Google Maps, Google Street View, PixAI, Stability.ai, ComfyUI API, and Bluesky.

- **Category:** AI Integration MCP Servers  
- **Slug:** `map-traveler-mcp`  
- **Source:** https://github.com/mfukushim/map-traveler-mcp

## Features

### Multi-service integration
- Connects LLMs to **Google Maps** for location search, map-based queries, and geographic context.  
- Integrates **Google Street View** for virtual exploration of real-world locations.  
- Uses **PixAI** for AI-generated images related to locations or scenes.  
- Supports **Stability.ai** for additional image generation and transformation capabilities.  
- Integrates **ComfyUI API** as a flexible backend for custom image workflows.  
- Connects with **Bluesky** for posting or interacting with location-related content within that social platform (as exposed via the MCP tools).

### Virtual location simulation
- Provides tools to simulate being in a given location using maps and Street View imagery.  
- Allows LLMs to retrieve and reason about geographic information (e.g., coordinates, nearby points of interest, visual context).  
- Supports workflows where text prompts, maps, and generated images are combined to create virtual travel narratives or environment simulations.

### MCP server capabilities
- Implements the **Model Context Protocol**, making all tools available as structured MCP tools to compatible LLM clients.  
- Packaged as a standalone server process that can be run locally or in a container (Dockerfile included).  
- Configuration via `server.json` for endpoints, credentials, and enabled services.  
- TypeScript-based codebase with shared configs (`tsconfig.*.json`).  
- Includes testing setup (`test` folder, `setupTests.ts`).

### Developer & deployment tooling
- **Docker** support via included `Dockerfile` for containerized deployment.  
- Uses **pnpm** for dependency management (`pnpm-lock.yaml`).  
- Database or schema tooling via **drizzle** configuration (`drizzle` folder and `drizzle.config.ts`).  
- GitHub CI / automation configuration under `.github`.  
- Smithery integration via `smithery.yaml` (e.g., for MCP discovery or packaging).

### Documentation & localization
- Main documentation in `README.md`.  
- Additional Japanese documentation in `README_jp.md`.

## Pricing
No pricing information is provided in the available content. The repository appears to be open source (a `LICENSE` file is present); check the GitHub project for license terms and any usage restrictions.
