# Rijksmuseum MCP Server

## Overview
A Model Context Protocol (MCP) server that connects to the Rijksmuseum API, allowing AI models and LLM-powered tools to explore, analyze, and interact with artworks and collections from the Rijksmuseum via natural language.

## Features
- **Artwork search (`search_artwork`)**  
  - Text-based search across the collection  
  - Filter by artist name  
  - Filter by artwork type  
  - Filter by materials and techniques  
  - Filter by time periods  
  - Filter by colors  
  - Additional query parameters supported by the Rijksmuseum API

- **Artwork details (`get_artwork_details`)**  
  - Retrieve detailed information for a specific artwork (e.g., metadata, description, and related fields exposed by the API)

- **Image tiles access**  
  - Interface with the Rijksmuseum image tile endpoints to obtain artwork imagery suitable for zooming or tiled viewing (as supported by the API)

- **User collections exploration**  
  - Tools for navigating and exploring Rijksmuseum user collections through LLM interactions (where available in the underlying API)

- **LLM-ready MCP integration**  
  - Exposes the above capabilities as MCP tools so they can be called directly by compatible LLM clients  
  - Designed for natural-language-driven exploration and analysis of the museum’s collection

## Pricing
- **Free & open source**  
  - Licensed under the MIT License (no usage fee for the server code itself; Rijksmuseum API usage is subject to the museum’s own terms).

## License
- **MIT License** – permissive open-source license as specified in the repository.