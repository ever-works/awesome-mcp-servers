## Overview

A Model Context Protocol (MCP) server for Selenium WebDriver — browser automation for AI agents. MCP (Model Context Protocol Server) is a middleware component that acts as a bridge between AI agents (like Claude AI) and browser automation tools such as Selenium WebDriver.

## Key Features

This server allows AI agents to control a web browser session via Selenium WebDriver, enabling:

- **Web Scraping**: Extract data from websites
- **Automated Testing**: Execute test scenarios
- **Form Filling**: Automate form submissions
- **Natural Language Control**: Describe test steps in natural language and have them executed programmatically

## Browser Support

Compatible with all major browsers:
- **Chrome**: Full support
- **Firefox**: Full support
- **Edge**: Full support
- **Safari**: macOS only (requires `sudo safaridriver --enable` and enabling "Allow Remote Automation" in Safari → Settings → Developer)

## Available Implementations

### Angie Jones' Implementation

Released by Angie Jones, a prominent figure in test automation, enabling browser automation through the Model Context Protocol (MCP) for Selenium WebDriver.

**GitHub**: angiejones/mcp-selenium

### Python Package

A powerful MCP server that brings Selenium WebDriver automation to AI assistants.

**Installation**: `pip install selenium-mcp-server`
**PyPI**: Available on PyPI

### Node.js Package

MCP Selenium Server bridges the gap between AI assistants and web browser automation. Built on the Model Context Protocol (MCP), it enables AI agents to interact with web browsers just like humans do.

**Features**:
- Clicking buttons
- Filling forms
- Taking screenshots
- Handling complex web interactions

**Installation**: `npm install @dhivakaranthonydoss/mcp-selenium`

## Benefits

MCP acts as a bridge between AI agents (like Claude or Copilot) and browser automation tools:

- Describe test steps in natural language
- Programmatic execution
- Reduced manual testing effort
- Automated quality assurance
- Repeatable test scenarios

## Use Cases

- Automated web testing
- Regression testing
- End-to-end test automation
- Web scraping and data extraction
- Form automation
- UI interaction testing
- Cross-browser compatibility testing

## Integration

Works with AI assistants and tools:
- Claude Desktop and Claude Code
- Cursor AI
- VS Code extensions
- Custom MCP clients

## Technical Capabilities

- Browser session management
- Element interaction (click, type, select)
- Page navigation
- Screenshot capture
- JavaScript execution
- Wait strategies
- Multiple window/tab handling
- Alert and popup management

## Pricing

Free and open-source. Browser driver costs may apply for cloud-based testing platforms.