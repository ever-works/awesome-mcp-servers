# Simplescraper MCP Server

**Category:** Content Extraction & Summarization MCP Servers  
**Website:** https://simplescraper.io/docs/mcp-server  
**MCP Endpoint:** `https://mcp.simplescraper.io/mcp`

Simplescraper MCP Server exposes Simplescraper’s web scraping and data extraction features to MCP-compatible AI applications (e.g., Claude, Cursor, ChatGPT). It lets agents manage scrape recipes and run extractions directly via MCP tools.

---

## Features

### MCP Integration
- Standards-based Model Context Protocol (MCP) server.  
- Accessible by AI applications that support MCP (e.g., Claude Desktop, Cursor IDE, others).  
- OAuth 2.1–protected connection to a Simplescraper account.

### Recipe Management Tools
- **`list_recipes`**  
  - Search and list existing recipes.  
  - Filter/fetch by:
    - Domain
    - Keyword
    - Recent activity

- **`get_recipe`**  
  - Retrieve full details for a specific recipe.  
  - Includes CSS selectors and configuration.

- **`create_recipe`**  
  - Create new scrape recipes.  
  - Define target URL and CSS selectors programmatically.

- **`update_recipe`**  
  - Modify existing recipes, including:
    - Name
    - URL
    - Selectors

### Data Extraction Tools
- **`run_recipe`**  
  - Execute a recipe to perform a fresh scrape and collect new data.

- **`smart_extract`**  
  - AI-powered extraction that does not require manual CSS selectors.  
  - Lets agents describe what to extract in natural language (e.g., product names, prices, ratings).

- **`get_latest_results`**  
  - Fetch the most recent scraped dataset for a recipe.

- **`get_results`**  
  - Retrieve specific scrape results by result ID.

- **`get_results_history`**  
  - Access historical scrape runs for a recipe.

### Batch Operations
- **`update_batch_urls`**  
  - Manage and update lists of URLs for batch scraping workflows.

### Example Usage Patterns
- Natural-language instructions to AI agents, such as:
  - Extracting structured product data from ecommerce pages using `smart_extract`.
  - Retrieving the latest scrape results for a specific source (e.g., a social profile scraper).

---

## Integration & Setup

### Claude Desktop
- Add Simplescraper as an MCP Server:
  - Name: `Simplescraper`
  - URL: `https://mcp.simplescraper.io/mcp`
- Complete the OAuth-based authentication flow to link your Simplescraper account.  
- Then control scraping, recipes, and data retrieval via natural language within Claude.

> Note: Claude Integrations are currently available on the Max plan (per the provided content).

### Cursor IDE

**Global Setup (all projects)**
1. Create `~/.cursor/mcp.json` in your home directory.  
2. Add an MCP server entry for Simplescraper pointing to `https://mcp.simplescraper.io/mcp` with an `Authorization: Bearer <token>` header.

**Project-Specific Setup**
1. Create `.cursor/mcp.json` in your project root.  
2. Use the same Simplescraper MCP configuration.  
3. Server becomes available only for that project.

**Via Cursor Settings UI**
1. Open Cursor Settings.  
2. Navigate to **MCP**.  
3. Click **Add Server**.  
4. Configure:
   - Name: `Simplescraper`
   - URL: `https://mcp.simplescraper.io/mcp`
5. Save and authenticate when prompted.

### Other MCP-Compatible AI Applications
- Add a new MCP server / tool configuration with:
  - URL: `https://mcp.simplescraper.io/mcp`
- Use the app’s standard MCP or tools settings to complete setup and authentication.

---

## Pricing

The provided content does not list dedicated pricing for the Simplescraper MCP server.  
It notes that Claude’s **Integrations** are currently available on the **Claude Max** plan, but this refers to Claude’s plan, not Simplescraper’s own pricing.

For up-to-date pricing of Simplescraper itself or access limits for the MCP server, refer to the main Simplescraper site or pricing/docs pages.