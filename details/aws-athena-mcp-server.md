## Overview

AWS Athena MCP Server is a Model Context Protocol (MCP) server that lets AI assistants run SQL queries against AWS Athena databases, using Glue Data Catalog tables as the schema source.

## Features

- **MCP-compatible server** for integrating AWS Athena with AI assistants and MCP clients.
- **Execute SQL queries on Athena** databases programmatically via MCP tools.
- **Glue Catalog integration** for querying tables defined in the AWS Glue Data Catalog.
- **AWS-native data access** leveraging Athena for serverless, SQL-based analytics on data in S3 (via Athena).
- **Repository assets** to support development and deployment:
  - `Dockerfile` for containerized deployment of the MCP server.
  - TypeScript-based source code (`src`, `tsconfig.json`).
  - Project configuration (`package.json`, `package-lock.json`).
  - CI/CD workflows under `.github/workflows`.
  - `DEVELOPMENT.md` for contributor/development guidance.

## Use Cases

- Querying Athena-backed datasets from AI assistants.
- Running ad-hoc or analytical SQL queries on Glue Catalog tables.
- Integrating AWS data sources into MCP-based tools or workflows.

## Pricing

- Open-source project; no pricing information is provided in the available content.

## License

- A `LICENSE` file is present in the repository; specific license details should be confirmed directly from that file.