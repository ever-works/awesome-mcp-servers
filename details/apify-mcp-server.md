# Apify MCP Server

**Category:** Workflow Automation – MCP Servers  
**Brand:** Apify  
**Slug:** apify-mcp-server  
**Source:** https://github.com/apify/apify-mcp-server  
**Website:** https://mcp.apify.com

## Overview

Apify MCP Server is a Model Context Protocol (MCP) server that connects AI agents to the Apify platform. It provides access to thousands of pre-built cloud tools (Apify Actors) for web scraping, crawling, and automation, enabling agents to extract and process data from social media, search engines, maps, e-commerce sites, and other websites.

## Features

- **MCP integration**  
  - Implements a server compatible with the Model Context Protocol for use with AI agents and MCP-enabled clients.

- **Access to Apify Actors**  
  - Connects to 3,000+ pre-built Apify Actors (scrapers, crawlers, automation tools) hosted on the Apify platform.  
  - Supports data extraction from websites, e-commerce platforms, social media, search engines, and map services.

- **Web scraping & crawling**  
  - Use ready-made scrapers and crawlers without building custom scraping logic.  
  - Leverage cloud execution on Apify for large-scale or complex scraping tasks.

- **Automation tools**  
  - Invoke automation workflows exposed as Apify Actors (e.g., form submissions, scheduled runs, page interactions) via MCP.

- **Configurable via environment**  
  - Example environment configuration provided in `.env.example` for setting necessary tokens and connection details (e.g., Apify API token).

- **Docker support**  
  - `.dockerignore` present for containerized deployment scenarios.  
  - Suitable for running the server inside Docker as part of a larger AI tooling stack.

- **Source-available and extensible**  
  - Full source code under the `src` directory for customization or extension of tools and behavior.  
  - Additional resources and examples in `docs`, `notebooks`, and `evals` directories.

- **Testing & quality**  
  - Automated tests provided under `tests`.  
  - GitHub Actions workflows under `.github/workflows` for CI-related tasks.

- **Project metadata**  
  - MIT-licensed open source project.  
  - Includes editor and git configuration files (`.editorconfig`, `.gitignore`) for consistent development.

## Pricing

- Not specified in the provided content.  
- The repository itself is open source under the MIT license; usage of Apify platform/Actors may be subject to Apify’s separate pricing and quotas (not detailed in the extracted content).

## Tags

- Web scraping  
- Automation  
- Integration

## Media

- **Logo:** https://apify.com/favicon.ico  
- **Image:** https://repository-images.githubusercontent.com/878215990/43db87c0-4b50-4c8a-87d4-37b2257f8bad