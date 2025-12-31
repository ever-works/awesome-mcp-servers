# Morningstar MCP Server

## Description
Morningstar MCP Server is an MCP (Model Context Protocol) server that lets AI applications securely access Morningstar’s financial content and data via `https://mcp.morningstar.com/mcp` using OAuth2.1. It exposes AI-ready tools for analyst research, market analysis, articles, and global investment data, including mutual funds, ETFs, and stocks.

## Features
- **MCP endpoint**
  - Public MCP server URL: `https://mcp.morningstar.com/mcp`
  - Designed for AI tools and applications via the Model Context Protocol
- **Authentication & Access**
  - Uses OAuth2.1 for secure authentication
  - Requires a licensed Morningstar account to connect and use the server
- **AI-ready Morningstar content**
  - Access to Morningstar’s global analyst research
  - Market analysis and commentary
  - Key investment and market data for mutual funds, ETFs, and stocks
- **Exposed MCP tools**
  - **morningstar-analyst-research-tool**
    - Returns relevant portions of Morningstar analyst- and quantitative-driven forward-looking investment reports
  - **morningstar-articles-tool**
    - Returns relevant portions of articles, news, and commentary from Morningstar.com and other Morningstar products
  - **morningstar-data-tool**
    - Retrieves Morningstar’s AI-ready data for global mutual funds, ETFs, and stocks
  - **morningstar-fund-holdings-tool**
    - Retrieves the top holdings for a list of mutual funds or ETFs
  - **morningstar-id-lookup-tool**
    - Acts as an entity detection layer
    - Identifies relevant investments and data points to route to other tools
  - **morningstar-screener-tool**
    - Retrieves a list of investments that match specified screening criteria
- **Integration with Claude (Claude for Enterprise)**
  - Morningstar MCP Server can be added as a custom connector in Claude for Enterprise
  - Admins configure the remote MCP server URL as `https://mcp.morningstar.com/mcp`
  - Users can connect to Morningstar from Claude via **Search and tools** or **Settings → Connectors**, then authenticate with their Morningstar account
- **Developer documentation & examples**
  - Additional pages for tools and example questions
  - Workflow examples for integrating Morningstar MCP Server in AI workflows
  - Related documentation within Morningstar Direct Web Services (e.g., data and research, screeners, time series, portfolio and scenario analysis) for broader API ecosystem context

## Integrations
- **Claude (Claude for Enterprise)**
  - Custom connector integration using the MCP endpoint
  - Admin and end-user flows for enabling and authenticating the connector

## Pricing
- Not specified in the provided content.
- Usage requires a **licensed Morningstar account**; specific pricing or plan details are not described.

## Access Requirements
- Licensed Morningstar account
- OAuth2.1-based authentication
- MCP-compatible AI client or environment (e.g., Claude for Enterprise with custom connector support).