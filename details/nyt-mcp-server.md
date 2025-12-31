# nyt MCP Server

An MCP server that integrates with the New York Times API to search recent NYT articles via the Model Context Protocol.

- **Category:** Web Search MCP Servers  
- **Tags:** news, api-integration, search  
- **License:** MIT  
- **Source:** https://github.com/angheljf/nyt

## Features

### NYTimes Article Search
- **TypeScript-based MCP server** for interacting with the New York Times API.  
- **Search scope:** NYTimes articles from the last 30 days.  
- **Primary tool:** `search_articles`
  - **Input parameters:**
    - `keyword` (required) – keyword to search for in NYTimes articles.  
  - **Output:** list of matching articles including:
    - Title  
    - Abstract  
    - URL  
    - Published date  
    - Author

### MCP Integration
- Implements core Model Context Protocol (MCP) concepts.  
- Exposes tools over MCP for use by compatible MCP clients.

### Development & Build
- Install dependencies with `npm install`.  
- Build the server with `npm run build`.  
- Development mode with auto-rebuild using `npm run watch`.  
- Debugging over stdio recommended via tools like MCP Inspector.

## Pricing

- Open-source project under the MIT License.  
- No pricing plans; free to use and modify subject to license terms.