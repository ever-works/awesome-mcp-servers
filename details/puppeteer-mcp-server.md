# Puppeteer MCP Server

**Website:** https://mcp.pipedream.com/app/puppeteer  
**Category:** Code Execution & Automation MCP Servers  
**Tags:** browser-automation, scraping, javascript

## Description
Puppeteer MCP Server is an MCP (Model Context Protocol) server that exposes Puppeteer’s Chrome/Chromium automation APIs to MCP-compatible clients. It allows you to control a headless (or full) browser from tools like ChatGPT and other MCP clients for scripting, automation, and web scraping tasks.

## Features
- **MCP server endpoint**
  - Static MCP server URL usable across clients: `https://mcp.pipedream.net/v2`
  - Authentication handled when adding the server to your MCP-compatible application.

- **Puppeteer-based browser control**
  - Built on Puppeteer, a Node.js library that provides a high-level API over the Chrome DevTools Protocol.
  - Enables automated interaction with Chrome/Chromium for scripting, scraping, and page inspection.

- **Available tools (actions)**
  - **Screenshot a Page**
    - Captures a screenshot of a web page using Puppeteer.
  - **Get PDF**
    - Generates a PDF version of a web page.
  - **Get Page Title**
    - Retrieves the `<title>` of a web page.
  - **Get HTML**
    - Fetches the HTML content of a web page.

- **Client integration**
  - Can be added to various MCP-compatible chat clients (e.g., ChatGPT / OpenAI) via the provided MCP server URL.
  - Configuration details available on the Pipedream MCP configuration page.

## Integration & Setup
- Sign in with a Pipedream account to connect and manage the Puppeteer MCP Server.
- Copy and use the static MCP server URL (`https://mcp.pipedream.net/v2`) when configuring your MCP client.

## Pricing
Pricing information is not provided in the available content.