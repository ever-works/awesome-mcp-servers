# content-core

**Description**

content-core is an open-source MCP server for intelligent content extraction from URLs, documents, videos, and audio files. It automatically selects the appropriate extraction engine and supports multiple content types, making it suitable as a backend component for AI workflows and tools that need structured text from diverse media sources.

**Key Details**

- **Type:** Open-source MCP server / content extraction tool
- **Category:** Content extraction & summarization MCP servers
- **License:** MIT
- **Source:** https://github.com/lfnovo/content-core

## Features

- **Multi-source content extraction**
  - Extracts content from web URLs
  - Handles documents (e.g., typical file-based content)
  - Processes video sources
  - Processes audio sources

- **Automatic engine selection**
  - Chooses the appropriate extraction engine based on input type
  - Aims to abstract away low-level handling of different media formats

- **Multi-format / multi-type support**
  - Designed to work across different media formats under a unified interface
  - Suitable for building pipelines that combine text from web, document, video, and audio sources

- **MCP server integration**
  - Implements the Model Context Protocol (MCP) for integration with AI assistants and tools that speak MCP
  - Can serve as a central content-ingestion component for AI workflows

- **Developer-focused repository assets**
  - `docs/` directory with project documentation
  - `examples/` directory for sample usage and integration patterns
  - `specs/` for protocol or API specifications
  - Tests included for core functionality

## Pricing

- content-core is open source under the MIT license. It can be used, modified, and self-hosted without licensing fees.
- No paid plans or commercial pricing tiers are listed in the provided content.