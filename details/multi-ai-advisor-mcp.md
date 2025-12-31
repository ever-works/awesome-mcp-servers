## Overview

**multi-ai-advisor-mcp** is an open‑source Model Context Protocol (MCP) server that queries multiple Ollama models in parallel and aggregates their responses. It enables a "council of advisors" pattern where an MCP‑compatible client (such as Claude) can review and synthesize multiple model perspectives on the same question.

- **Category:** AI Integration – MCP Servers  
- **Use case:** Aggregated AI advice, analysis, and comparison of multiple LLM outputs via Ollama.

## Features

- **Multi‑model querying via Ollama**  
  - Sends a user query to multiple Ollama‑hosted language models.  
  - Supports getting diverse answers for the same prompt from different models.

- **Aggregated / combined responses**  
  - Collects responses from all configured models.  
  - Presents results in a form suitable for synthesis by a client model (e.g., Claude acting as a meta‑advisor).  
  - Enables comparison of viewpoints, reasoning styles, or recommendations across models.

- **"Council of advisors" pattern**  
  - Designed so a primary LLM (like Claude) can treat the other Ollama models as a virtual panel of experts.  
  - Facilitates more comprehensive answers by drawing on multiple perspectives.

- **MCP server implementation**  
  - Implements the Model Context Protocol for integration with MCP‑aware clients.  
  - Distributed as a standalone server that can be run locally or containerized.

- **Ollama integration**  
  - Uses Ollama as the backend for all queried models.  
  - Compatible with any models you have available in your Ollama setup.

- **Configurable environment**  
  - Uses an `.env` file for configuration (e.g., Ollama host, model list, or related settings).  
  - Includes TypeScript config (`tsconfig.json`) and NodeJS package configuration for customizing or extending the server.

- **Container support**  
  - Includes a `Dockerfile` for running the MCP server in a containerized environment.

- **Smithery integration**  
  - Can be installed for Claude Desktop via Smithery using the published server definition.  
  - Provides a ready‑made `smithery.yaml` for straightforward setup.

- **Open‑source licensing**  
  - Distributed with a `LICENSE` file (open‑source; see repository for exact terms) allowing modification and self‑hosting.

## Installation & Setup

- Install via Smithery for Claude Desktop using the provided Smithery server link.  
- Alternatively, clone the GitHub repository and use NodeJS tooling (`package.json`, `package-lock.json`) to install dependencies and run the MCP server.  
- Optional: build and run via Docker using the included `Dockerfile`.  
- Configure runtime options through the `.env` file.

## Pricing

- No pricing information is provided. The project is open‑source on GitHub; use is governed by the included license rather than a commercial pricing plan.