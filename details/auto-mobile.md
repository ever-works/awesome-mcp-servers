# auto-mobile

**Category:** Code Execution & Automation – MCP Servers  
**Brand:** Zillow  
**Source:** https://github.com/zillow/auto-mobile

## Overview

auto-mobile is a mobile automation suite of tools centered around an MCP (Model Context Protocol) server, providing automation capabilities and libraries for authoring and executing tests. It is designed to support mobile developer workflows and testing, with a focus on Android (and a repository structure that also includes iOS).

## Features

- **MCP-based automation server**
  - Provides an MCP server interface for driving mobile automation.
  - Exposes automation capabilities via MCP for integration with MCP-compatible clients and tools.

- **Mobile test authoring libraries**
  - Libraries intended for writing automated tests against mobile applications.
  - Organized support for Android, with an `android` directory containing platform-specific code.
  - Presence of an `ios` directory indicating iOS-related components or structure (details not visible in provided content).

- **Test execution tooling**
  - Tooling for running mobile tests, using the same suite and libraries that integrate with the MCP server.
  - A `test` directory for test code and examples (based on repository layout).

- **Multi-platform project layout**
  - Separate directories for `android` and `ios` platform code.
  - `src` directory for core/shared logic.
  - `scripts` and `logs` directories for automation scripts and run-time logs.

- **Developer-focused ecosystem files**
  - Configuration and tooling files such as `.mocharc.json` (Mocha test runner configuration) and `eslint.config.mjs` (linting), suggesting a Node.js/TypeScript or JavaScript-based tooling layer.
  - `CHANGELOG.md` for version history and `CODE_OF_CONDUCT.md`, `SECURITY.md`, and `DISCLAIMER.md` for project governance and security practices.

- **Open source licensing**
  - Includes a `LICENSE` file (exact license type not readable from snippet, but the project is distributed with an explicit open source license file).

## Pricing

- No pricing information is provided. The project is hosted on GitHub with a LICENSE file, indicating it is open source rather than a paid product or SaaS plan.
