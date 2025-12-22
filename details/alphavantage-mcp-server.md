## AlphaVantage MCP Server

**Description**

Official Model Context Protocol (MCP) server for the Alpha Vantage stock market data API. It enables LLMs and MCP-compatible tools to fetch real-time and historical financial and market data from Alpha Vantage.

**Category**

- MCP server directories & lists

**Features**

- **MCP server for Alpha Vantage**: Exposes the Alpha Vantage stock market data API via the Model Context Protocol.
- **Real-time market data access**: Allows LLMs to retrieve up-to-date stock market information (via Alpha Vantage).
- **Historical data retrieval**: Supports access to historical financial and market time series (via Alpha Vantage).
- **Official implementation**: Described as the official Alpha Vantage MCP server in the repository README.
- **AWS Lambda deployment assets**: Includes a `deploy/aws-stateless-mcp-lambda` directory for deploying the MCP server in a stateless AWS Lambda setup.
- **Containerization support**: Provides a `Dockerfile` for building and running the MCP server in Docker-based environments.
- **Python-based project**: Managed via `pyproject.toml` with a defined Python version (`.python-version`).
- **Testing setup**: Includes a `tests` directory and `pytest.ini` for automated testing.
- **Repository configuration & automation**: Contains `.github` workflows/configs and `.bumpversion.cfg` for release/version management.
- **Development documentation**: `DEVELOPMENT.md` and `CONTRIBUTING.md` files to guide local development and contributions.

**Pricing**

- Not specified in the provided content (open-source GitHub repository; refer to the repository and Alpha Vantage directly for any usage or API costs).