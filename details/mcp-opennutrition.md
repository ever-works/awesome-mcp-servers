# mcp-opennutrition

## Overview
mcp-opennutrition is a local Model Context Protocol (MCP) server that provides programmatic access to the OpenNutrition database, offering search over more than 300,000 food items, detailed nutrition facts, and barcode-based lookups.

- **Type:** Open-source MCP server
- **Category:** Data access & integration (MCP servers)
- **Developer / Brand:** deadletterq
- **License:** GPL-3.0
- **Source code:** https://github.com/deadletterq/mcp-opennutrition

## Features
- **Local MCP server implementation**
  - Runs as a local service compatible with the Model Context Protocol.
  - Designed to integrate with MCP-capable clients and tools.

- **Comprehensive food database access**
  - Interfaces with the OpenNutrition database.
  - Provides access to **300,000+ food items**.

- **Nutrition facts retrieval**
  - Returns detailed nutritional information for foods from the OpenNutrition dataset.

- **Barcode lookup support**
  - Enables lookups of food items by barcode and returns associated nutritional data when available.

- **Structured data access**
  - Exposes food and nutrition information in a structured, machine-readable format suitable for automation and integration.

- **Open-source project structure**
  - Source organized into `src`, `data`, and `scripts` directories.
  - Includes TypeScript configuration (`tsconfig.json`) and Node.js package definitions (`package.json`, `package-lock.json`).

## Use Cases
- Building nutrition-aware applications or agents that query foods by name or barcode.
- Integrating large-scale nutrition data into MCP-compatible AI tooling.
- Automating diet, meal planning, or food logging workflows with structured nutritional facts.

## Pricing
- **Open-source / Free**
  - Distributed under the GPL-3.0 license.
  - No pricing plans are listed; usage is governed by the open-source license terms.