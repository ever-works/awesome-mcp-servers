# Token Metrics MCP Server

**Category:** Finance / Market Data MCP Servers  
**Slug:** `token-metrics-mcp-server`

An MCP server that exposes Token Metrics’ cryptocurrency analytics and AI-driven insights, enabling chat clients and MCP-compatible tools to discover, evaluate, and analyze crypto assets via structured actions.

---

## Features

### MCP Server & Access
- Static MCP server URL for all clients: `https://mcp.pipedream.net/v2`  
- Works with multiple chat / MCP-compatible applications.  
- Authentication performed when adding the server to your application.  
- 25 actions exposed as tools (individual actions documented in the Token Metrics components on GitHub).

### Market Data & Asset Discovery
- **Get Top Market Cap Tokens**  
  - Retrieve a list of tokens with the highest market capitalization.
- **Get Tokens**  
  - List coins supported by Token Metrics and their `TOKEN_ID`.  
  - Includes key market data such as:  
    - Contract address  
    - Current price  
    - Market cap  
    - Trading volume  
    - Supply metrics  
    - 24-hour price change.
- **Get Price**  
  - Fetch token prices based on provided token IDs.

### Trading Signals & AI Insights
- **Get Trading Signals**  
  - AI-generated trading signals for long and short positions across supported tokens.

### Token Metrics (TM) Grades & Historical Analytics
- **Get TM Grades**  
  - Latest TM Grade for a token, including:  
    - Trader grade change  
    - Quant grade  
    - Signals  
    - Momentum  
    - 24-hour percentage change for TM Grade  
    - 24-hour percentage change for Trader Grade.
- **Get TM Grades Historical**  
  - Historical TM Grade data over time, including:  
    - Trader grade change history  
    - Quant grade history  
    - Signals and momentum history  
    - 24-hour percentage changes for TM Grade and Trader Grade over time.

### Technology & Fundamental Analytics
- **Get Technology Grades**  
  - Technology Grade insights for a token, including:  
    - Activity score  
    - Security score  
    - Repository score  
    - Collaboration score  
    - DeFi scanner score.
- **Get Technology Grades Historical**  
  - Historical Technology Grade data over time, including:  
    - Activity score history  
    - Security score history  
    - Repository score history  
    - Collaboration score history  
    - DeFi scanner score history.

### Quantitative Metrics & Price Analytics
- **Get Quantmetrics**  
  - Latest quantitative metrics for tokens.  
  - Pricing data coverage generally starts from 2019-01-01 for most tokens (with older data to be expanded as available).

### Technical Levels & Market Structure
- **Get Resistance & Support**  
  - Historical resistance and support levels for each token.

> Note: The page indicates 25 tools/actions are available; only the actions explicitly listed in the provided content are summarized here.

---

## Pricing

Pricing information is not provided in the available content.