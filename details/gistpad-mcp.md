# gistpad-mcp

**Category:** document-management-mcp-servers  
**Website/Source:** https://github.com/lostintangent/gistpad-mcp

## Overview

gistpad-mcp is an open-source MCP (Model Context Protocol) server that lets LLM-based tools manage and access your personal knowledge base using GitHub Gists. It is designed as a companion to the GistPad VS Code extension and GistPad.dev, enabling AI clients (e.g., GitHub Copilot, Claude Desktop) to read, create, and update your gists as notes, daily logs, and reusable prompts.

## Features

- **GitHub Gists as a knowledge base**  
  - Uses your GitHub Gists to store and organize personal notes, documentation, and other knowledge.  
  - Treats gists as a structured source of context for LLMs.

- **MCP server integration**  
  - Implements the Model Context Protocol so that any MCP-capable AI client can connect.  
  - Works with tools like GitHub Copilot Chat (Agent mode) and Claude Desktop.

- **Personal notes and documentation**  
  - Store and manage notes as gists.  
  - Ask natural-language questions over your existing gists (e.g., summaries, counts, references).

- **Daily notes / journaling**  
  - Use gists as daily logs or journals that the LLM can reference and update.

- **Reusable prompts and snippets**  
  - Save reusable prompts, templates, or code snippets as gists for quick retrieval and reuse by AI tools.

- **Content exploration via LLM**  
  - Query statistics like how many gists you have edited in a given timeframe.  
  - Request summaries of specific gists.

- **Content creation and editing via LLM**  
  - Create new gists from natural-language instructions.  
  - Update existing gists (e.g., modify sections, add callouts, refine content) through AI.

- **GistPad ecosystem integration**  
  - Companion to the GistPad VS Code extension for editing and browsing gists directly in VS Code.  
  - Integrates with GistPad.dev for web/mobile access to the same gist-backed knowledge base.

- **GitHub authentication**  
  - Supports GitHub sign-in via GistPad in VS Code.  
  - For other MCP clients, uses a GitHub Personal Access Token limited to the `gist` scope for secure access.

- **Configuration via MCP client**  
  - Connectable through MCP config files or “Add MCP server” UI flows in compatible clients.

## Setup & Usage (High-Level)

- **With VS Code + GistPad**  
  - Install the GistPad extension (requires VS Code 1.101.0+).  
  - Open the GistPad tab and sign in with GitHub.  
  - Use Copilot Chat in Agent mode to interact with your gists via gistpad-mcp.

- **With other MCP clients**  
  - Create a GitHub Personal Access Token with only the `gist` scope.  
  - Add gistpad-mcp to your MCP client configuration (or through its UI) using that token.  
  - Run natural-language commands such as:  
    - “How many gists have I edited this month?”  
    - “What’s the summary of my `<foo>` gist?”  
    - “Create a new gist about `<foo>`.”  
    - “Update my `<foo>` gist to call out `<bar>`.”

## Pricing

- Not specified in the available content. The project appears to be an open-source GitHub repository; no pricing plans are mentioned.

## License

- A `LICENSE.txt` file is present in the repository; specific license terms are not detailed in the provided content and should be checked directly in the file.