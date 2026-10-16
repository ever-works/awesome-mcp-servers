## Overview

[Fillfolio MCP](https://github.com/fillfolio/portfolio-mcp) provides read-only access to the portfolio and financial records stored in a Fillfolio account: stocks, ETFs, funds, crypto, cash, liabilities, investment activity, bank spending and budgets.

## Connection and access

- Endpoint: `https://fillfolio.com/api/mcp`
- Transport: Streamable HTTP
- Authentication: OAuth authorization code with PKCE; the client identity and callback must be accepted by Fillfolio.
- Access: a paid Fillfolio account; spending and budgets require an eligible plan, bank-spending consent and separate per-client permissions.
- Setup: [MCP reference](https://fillfolio.com/mcp) and [client guide](https://github.com/fillfolio/portfolio-mcp-skills/blob/main/docs/client-setup.md).

The tools read stored records. They cannot trade, move money, edit budgets or trigger provider refreshes. Responses retain currencies, coverage warnings and synchronization information. A response time does not establish live quote freshness.

The public repository contains MIT-licensed contracts, documentation and helpers. The hosted server implementation is private. [Fifteen companion skills](https://github.com/fillfolio/portfolio-mcp-skills) provide reusable workflow instructions; their MIT files are free, while authenticated workflows still require Fillfolio access.
