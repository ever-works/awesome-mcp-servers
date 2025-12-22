# Puppeteer

**Category:** MCP server directories & lists  
**Slug:** `puppeteer`

## Description
Puppeteer is an MCP (Model Context Protocol) server that uses Puppeteer for browser automation and web scraping. It allows LLMs to interact with and capture dynamic web content that requires a real browser environment.

**Source:** <https://github.com/madhukarkumar/anthropic-mcp-servers/blob/main/src/puppeteer>

## Features
- **MCP server implementation**
  - Exposes browser-related capabilities through the Model Context Protocol.
  - Designed to be used by LLMs and MCP-compatible clients.

- **Puppeteer-based browser automation**
  - Uses Puppeteer to control a headless (or full) browser.
  - Can programmatically open web pages and navigate between URLs.

- **Web scraping and content capture**
  - Extracts information from web pages via an automated browser.
  - Supports capturing content from dynamic sites that rely on client-side rendering.

- **Dynamic web interaction for LLMs**
  - Enables LLMs to interact with live web pages rather than static HTML only.
  - Provides access to up-to-date, dynamically generated page content.

## Typical Use Cases
- Scraping data from JavaScript-heavy or dynamically rendered websites.
- Automating browsing flows (navigation, interactions) for information retrieval.
- Enabling an LLM to read and reason about dynamic web pages within an MCP-compatible environment.

## Pricing
- Not specified in the provided content.

## Links
- **Source code:** <https://github.com/madhukarkumar/anthropic-mcp-servers/blob/main/src/puppeteer>