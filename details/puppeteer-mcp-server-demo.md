# Puppeteer MCP Server Demo

**Description:**
A demo MCP (Model Context Protocol) server built around Puppeteer that lets Warp agents drive headless or visible browser sessions for tasks like scraping product reviews, automating navigation, and running web workflows directly from natural language prompts.

**Source:** <https://docs.warp.dev/university/mcp-servers/puppeteer-mcp-scraping-amazon-web-reviews>

---

## Features

- **Warp + Puppeteer Integration**
  - Connects Warp’s agents to a Puppeteer-powered browser via an MCP server.
  - Allows Warp to issue Puppeteer commands directly from prompts (no manual scripting required).

- **MCP Configuration in Warp**
  - Configured via the MCP Panel in Warp (opened through the Command Palette).
  - Uses a JSON configuration block to register the Puppeteer MCP server.
  - Exposes Puppeteer actions as MCP tools/endpoints, including:
    - `puppeteer.navigate`
    - `puppeteer.fill`
    - `puppeteer.screenshot`
    - `puppeteer.evaluate`

- **Browser Automation Capabilities**
  - Automates navigation across web pages.
  - Fills forms and search fields.
  - Takes screenshots of pages for later reference.
  - Evaluates custom JavaScript in the page context for scraping or interaction.
  - Supports both fully headless and visible browser modes.

- **Voice-Driven Automation**
  - Supports voice input in Warp to trigger automated browser workflows.
  - Users can describe tasks naturally; Warp translates them into Puppeteer MCP tool calls.

- **Data Scraping & Extraction**
  - Demonstrated workflow for scraping Amazon product and review data:
    - Navigates to Amazon and runs a product search.
    - Scrapes product results including titles, prices, and product links.
    - Visits individual product pages.
    - Extracts review data using JavaScript selectors.
    - Captures screenshots of pages as part of the run.

- **AI-Based Analysis & Summarization**
  - After scraping, Warp compiles structured data (e.g., product, price, rating, summary).
  - Generates ranked lists of items based on scraped attributes.
  - Produces natural-language summaries and recommendations from the scraped data.

- **Hands-Free Workflow Execution**
  - Once configured, workflows run autonomously without manual browser interaction.
  - Intended for “hands-free” execution combining MCP tools, Puppeteer, and Warp’s AI.

- **Reusable Across Scenarios**
  - Same MCP + Puppeteer setup can be applied to:
    - Product research (comparing reviews/specs across sites).
    - Competitive analysis (scraping competitor pricing or product data).
    - Web testing (automating flows like login and checkout).
    - Repetitive data tasks (periodic scraping or screenshot capture).

---

## Use Cases

- Scraping e-commerce product and review data (e.g., Amazon).
- Automating multi-step browser workflows from natural language or voice.
- Generating ranked product lists and summaries from scraped content.
- Running recurring web data collection jobs (prices, reviews, screenshots).
- Automating QA or user-flow checks on web applications.

---

## Pricing

Pricing details for the Puppeteer MCP Server Demo are **not specified** in the provided content.