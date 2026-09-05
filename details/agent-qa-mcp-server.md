# Agent QA MCP Server

Agent QA provides an MCP server that lets AI agents author, queue, and inspect natural-language application tests for web, Android, and iOS.

## Features

- Author and validate test definitions through MCP tools.
- Queue test and suite runs, then inspect their steps, logs, and artifacts.
- Retrieve structured run information for failure triage.
- Use Agent QA's persistent execution memory and recovery from UI changes during test execution.

## Integration

The `@vostride/agent-qa-mcp` package ships with Agent QA. The `agent-qa mcp` CLI command starts a server over standard input/output for MCP clients. Authoring and run-management tools require a configured Agent QA dashboard service; execution also requires the appropriate model and browser or device providers.

## License and Costs

Agent QA is source-available under FSL-1.1-ALv2. Each release converts to Apache-2.0 after two years. There is no software fee for permitted use; configured model, browser, and device providers may charge separately.

## Links

- [Repository](https://github.com/vostride/agent-qa)
- [Documentation](https://vostride.com/docs/agent-qa)
- [MCP setup and tool reference](https://vostride.com/docs/agent-qa/mcp)
