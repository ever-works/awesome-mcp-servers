## Overview

geolint is an open-source linter for AI search readiness ("ESLint for AI search"). It audits whether websites are discoverable and citable by AI answer engines: robots.txt evaluated across 51 AI crawler tokens, llms.txt validation, structured data and citability — 52 rules with a 0–100 score and a concrete fix per finding.

## Features

- `audit_url` — full AI-search readiness audit with score, grade and findings
- `compare_urls` — diff two URLs' findings and scores
- `generate_llms_txt` — crawl a site and generate a spec-conformant llms.txt
- `list_rules` / `list_ai_bots` — inspect the rule and bot registries
- SARIF output for GitHub code scanning, sticky PR comments via GitHub Action
- Published in the official MCP registry as `io.github.iliasabk/geolint`

## Pricing

Free and open-source under the MIT license.
