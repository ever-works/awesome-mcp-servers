# Indeed MCP Server

## Overview
The Indeed MCP Server is a Bright Data–hosted Model Context Protocol (MCP) server that connects MCP-compatible clients (such as AI agents) to public Indeed data. It enables programmatic extraction of public job postings, company information, salaries, ratings, reviews, and application details at scale, while excluding private or login-required content.

- **Provider:** Bright Data
- **Data source:** Public Indeed pages (jobs, companies, salaries, reviews)
- **Protocol:** MCP (Model Context Protocol)
- **Auth:** OAuth 2.1 (for integration with MCP-compatible clients)
- **Intended use:** Job search analysis, recruiting intelligence, HR analytics, market and salary research

## Features

### Public Indeed Data Extraction
- Scrape only **public** Indeed content; excludes private or login-required data.
- Extract public **job postings**, including:
  - Job titles
  - Descriptions
  - Locations
  - Employers/companies
  - Relevant metadata available on public listings
- Collect **company profiles**, including public company page content.
- Retrieve **salary information** from public salary pages.
- Access **ratings and reviews** from public employer review sections.
- Pull **application details** exposed on public job posting pages.

### Search Capabilities
- Extract **up-to-date** public job listings from Indeed.
- Search and filter jobs by:
  - **Region / geography** (e.g., country, city, locale) for localized labor market analysis.
  - **Category / domain** (e.g., job type, industry, specialization) for targeted recruiting or research.
- Collect and structure:
  - **Job URLs** for reference or downstream processing.
  - **Company records** associated with job listings.
  - **Salary data** for compensation benchmarking and analytics.

### Crawling & Scale
- Crawl **entire sets of public job listings** or **company pages**, not just individual URLs.
- Support large-scale public data collection from Indeed for:
  - Hiring funnels and recruitment pipelines.
  - Market and competitor research.
  - HR and workforce analytics.
- Output data in **structured, agent-ready formats** suitable for direct use by MCP clients or AI agents.
- Scale crawling intensity and breadth according to project requirements.

### Access & Reliability
- Provide reliable access to public Indeed pages, including:
  - Job listings
  - Company pages
  - Salary pages
  - Employer review pages
- Automatically handle common web access challenges:
  - **Geo-restrictions** (location-based access controls)
  - **CAPTCHAs**
  - **Dynamic content** (e.g., infinite scroll, dynamic job listing updates)
- Render **JavaScript-heavy pages**, ensuring full access to dynamically loaded Indeed content.

### Navigation & Automation
- Automate navigation flows that resemble real user behavior on Indeed.
- Monitor over time:
  - **New job postings** for specific roles, regions, or companies.
  - **Company profile updates** (e.g., description, reviews).
  - **Salary changes** and updated compensation ranges.
- Use **remote browser sessions** for:
  - More robust scraping of dynamic or protected public pages.
  - Accurate simulation of job seeker interactions.
- Simulate **real job seeker behavior** to improve access reliability and reduce blocking.

### MCP Integration
- Designed as a **single MCP server** that can be used for web-based data extraction, tailored here for public Indeed data.
- Integrates with MCP-compatible tooling (e.g., AI agents, orchestrators, playgrounds like Smithery) for:
  - Real-time data retrieval inside chat or agent workflows.
  - Automated pipelines for recruitment and HR analytics.

## Pricing
The provided content does not list specific pricing plans or rates for the Indeed MCP Server. Users are directed to "Start Free" / "Start Free Trial" options, but no detailed plan structure or pricing tiers are specified in the source content.
