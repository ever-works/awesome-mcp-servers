## Overview

**TMDB MCP Server** is an open-source Model Context Protocol (MCP) server that integrates with **The Movie Database (TMDB)** API. It enables LLM agents and MCP-compatible clients to access TMDB movie data programmatically, including metadata, search, and recommendation functions.

- **Repository:** https://github.com/Laksh-star/mcp-server-tmdb  
- **License:** MIT  
- **Brand / Data Source:** The Movie Database (TMDB)

## Features

- **TMDB integration**  
  - Connects directly to The Movie Database (TMDB) API.  
  - Provides structured movie-related data for use inside LLM workflows.

- **Movie metadata access**  
  - Retrieve detailed movie information (e.g., core metadata exposed by TMDB such as titles, overviews, and related attributes, as supported by the underlying API and server tools).

- **Search capabilities**  
  - Query TMDB for movies using search endpoints exposed through the MCP server.  
  - Designed so LLM agents can perform movie lookups dynamically in conversation.

- **Recommendation capabilities**  
  - Access TMDB-powered recommendation data via MCP tools.  
  - Intended for use in building movie discovery and suggestion workflows for agents.

- **MCP-compatible server**  
  - Implements the Model Context Protocol, making the TMDB tools available to MCP-aware clients and agents.  
  - Allows LLMs to call movie/search/recommendation tools as part of tool-augmented reasoning.

- **HTTP server entry point**  
  - `server-http.js` provided as an HTTP-based server entry, suitable for running the MCP server as a standalone service.

- **Containerization support**  
  - `Dockerfile` included to build and run the server in a containerized environment.

- **TypeScript / Node.js codebase**  
  - Source located under `src/` with `tsconfig.json` and `package.json` for TypeScript and Node.js tooling.

- **Smithery configuration**  
  - `smithery.yaml` included, indicating configuration for integration with Smithery or compatible MCP tooling ecosystems.

## Pricing

- **Open-source / Free**  
  - Licensed under the MIT License.  
  - No usage fee for the server itself (TMDB API usage remains subject to TMDB’s own terms and limits).