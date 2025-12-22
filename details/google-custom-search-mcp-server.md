## Description

Google Custom Search MCP Server is an open‑source Model Context Protocol (MCP) server that integrates the Google Custom Search API to provide web search capabilities and webpage content extraction to MCP‑compatible clients.

## Features

- **Model Context Protocol server**  
  - Implements an MCP server that tools/clients can connect to for search and content retrieval.

- **Google Custom Search integration**  
  - Uses the Google Custom Search API as the underlying search provider.  
  - Allows MCP clients to retrieve Google search results via the configured Custom Search Engine.

- **Web search capabilities**  
  - Performs web searches and returns structured results suitable for programmatic consumption by MCP clients.

- **Webpage reading / content extraction**  
  - Fetches web pages corresponding to search results (or other URLs) and extracts their content for use within MCP sessions.

- **Self‑hostable server**  
  - Distributed as source code that can be run as a service in your own environment.

- **Containerization support**  
  - Includes a `Dockerfile` for building and running the MCP server in a containerized environment.

- **TypeScript/Node.js implementation**  
  - Implemented in TypeScript (with `tsconfig.json`) and packaged via Node.js (`package.json`, `package-lock.json`).

- **Open‑source license**  
  - Released under the MIT License.

## Pricing

- **Project**: Open‑source and free to use under the MIT License.  
- **External API costs**: Any usage of the Google Custom Search API is subject to Google’s own pricing and quotas, which are not defined in this repository.