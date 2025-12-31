## mcp-screenshot-website-fast

**Category:** Media Processing MCP Servers  
**Tags:** screenshot, web, image-processing  
**License:** MIT  
**Source:** https://github.com/just-every/mcp-screenshot-website-fast

### Overview
`mcp-screenshot-website-fast` is an MCP server that quickly captures website screenshots and exposes this capability as MCP tools. It is optimized for use with Claude Vision by automatically tiling full-page screenshots into 1072×1072 image chunks suitable for LLM consumption.

### Features
- **Fast website screenshot capture**  
  - Automates taking screenshots of webpages via an MCP server interface.
- **Optimized for Claude Vision / LLMs**  
  - Converts full-page screenshots into a size and format that’s friendly for large vision models.
- **Automatic tiling of full pages**  
  - Splits long webpages into multiple 1072×1072 image tiles.  
  - Ensures consistent tile dimensions across the page for reliable model input.
- **MCP tools integration**  
  - Exposes screenshot functionality as MCP tools, enabling programmatic access from MCP-compatible clients or agents.
- **Full-page handling**  
  - Designed to process entire webpages, not just the visible viewport, before tiling.
- **Scripted/CLI usage** (implied by repo layout)  
  - Contains `bin` and `scripts` directories, indicating command-line or scripted usage patterns for automation.
- **Tested project structure**  
  - Includes a `test` directory for automated tests, suggesting coverage for core screenshot and tiling behavior.

### Pricing
- Not applicable (open-source project under the MIT license; no pricing plans listed).