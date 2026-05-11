## Overview

jpcite (PyPI package `autonomath-mcp`) is a Japanese public-program evidence MCP server. It surfaces structured access to 11,601 searchable programs (補助金 / 融資 / 税制 / 認定), 9,484 e-Gov laws, 22,258 enforcement detail rows, 13,801 国税庁 invoice registrants (PDL v1.0 attribution), 503,930 corporate entities, and 6.12M facts via 139 MCP tools at protocol 2025-06-18 (stdio transport).

## Features

- 139 MCP tools — search programs, look up laws, query enforcement, verify invoice registrants, traverse entity-fact relations.
- Every evidence packet preserves `source_url`, `source_fetched_at`, and `known_gaps` for citation verification.
- Primary-source lineage only (government ministries, prefectures, 日本政策金融公庫, 国税庁); aggregator URLs are banned.
- FTS5 with trigram tokenizer for Japanese phrase queries.
- Active on the official MCP Registry as `io.github.shigetosidumeda-cyber/autonomath-mcp` (v0.3.4).
- Install: `uvx autonomath-mcp` or `pip install autonomath-mcp`.

## Pricing

- Anonymous tier: 3 requests per day per IP, free (JST 翌日 00:00 reset, no key required).
- Metered tier: ¥3 per billable unit (税込 ¥3.30), no SKU tiers, no seat fees, no monthly minimum.
