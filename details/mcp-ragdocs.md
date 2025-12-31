# mcp-ragdocs

An MCP server that exposes retrieval and processing tools over documentation using vector search, allowing AI assistants to augment their responses with relevant documentation context.

- **Category:** content-extraction-summarization-mcp-servers  
- **Tags:** rag, documentation, semantic-search  
- **Source:** https://github.com/hannesrudolph/mcp-ragdocs

---

## Features

### Retrieval-Augmented Documentation Search
- Vector-based semantic search over stored documentation.  
- Natural-language query interface via the `search_documentation` tool.  
- Returns matching excerpts with surrounding context.  
- Results ranked by relevance.  
- Configurable result limit via `limit` input.

### Documentation Source Management
- `list_sources` tool provides a full overview of indexed documentation:  
  - Lists all stored documentation sources.  
  - Includes metadata such as source URLs, titles, and last update times.  
  - Useful to verify if specific sources have been indexed and are available for search.
- `remove_documentation` tool (incomplete description in source but clearly present):  
  - Removes documentation sources by URL.  
  - Removal is permanent and affects future search results.

### Web Page URL Extraction & Ingestion Support
- `extract_urls` tool for working with external web pages:  
  - Crawls a specified web page and identifies all hyperlinks.  
  - Extracts and analyzes URLs found on the page.  
  - Supports optional queuing of discovered URLs for further processing/ingestion via `add_to_queue` input.  
- Inputs:  
  - `url`: target web page to inspect.  
  - `add_to_queue`: flag to add discovered links to the processing queue.

### MCP Integration
- Implemented as an MCP server for use with MCP-compatible LLM tools/clients.  
- Designed so AI assistants can call tools to retrieve and ground responses in documentation.

---

## Tools Overview

- **search_documentation**  
  - Inputs: `query`, `limit`  
  - Purpose: Semantic search across stored docs; returns relevant excerpts with context.

- **list_sources**  
  - Inputs: (not specified)  
  - Purpose: Enumerate all indexed documentation sources with metadata (URL, title, last update time).

- **extract_urls**  
  - Inputs: `url`, `add_to_queue`  
  - Purpose: Crawl a page, extract all hyperlinks, optionally add them to a processing queue.

- **remove_documentation**  
  - Inputs: (not fully specified, but by URL)  
  - Purpose: Permanently delete selected documentation sources so they no longer appear in searches.

---

## Pricing

- Open-source project on GitHub; no pricing information or paid plans are specified in the available content.

---

## License

- Repository contains a `LICENSE` file; specific license terms should be confirmed directly in the project’s GitHub repository.