# mcp-pointer

## Overview
mcp-pointer is an open-source MCP server and Chrome extension that adds a visual DOM element selector to agentic coding tools (e.g., Claude Code, Cursor). It lets users point at elements in the browser so MCP-enabled AI coding environments can reference and work with the exact parts of a web page the user is looking at.

- **Category:** Development Tools – MCP Servers  
- **Brand:** etsd-tech  
- **License:** MIT  
- **Source:** https://github.com/etsd-tech/mcp-pointer

## Features
- **Visual DOM element selection**  
  - Allows users to click or point at DOM elements in the browser UI.  
  - Captures information about the selected element for use by AI coding tools.

- **Chrome extension integration**  
  - Runs as a Chrome extension to interact directly with pages open in the browser.  
  - Acts as the front-end capture layer for DOM elements and context.

- **MCP server for AI tools**  
  - Implements the Model Context Protocol (MCP) as a server backend.  
  - Exposes selected DOM element data to MCP-compatible agentic coding tools such as Claude Code and Cursor.  
  - Serves as a bridge between the browser and MCP-enabled environments.

- **Context synchronization**  
  - Designed so AI tools can “see what you see” in the browser.  
  - Helps align the AI’s understanding of the page structure with the user’s current view and selections.

- **Open-source project**  
  - Source code available on GitHub under the MIT license.  
  - Can be self-hosted, modified, or integrated into custom MCP workflows.

## Pricing
- Not specified in the provided content. The project is released under the MIT open-source license; usage is generally free under that license, subject to its terms.
