# ReMCP

**Category:** Server Management Tools  
**Source:** [Official ReMCP open-source device runtime](https://github.com/getremcp/remcp)

ReMCP is a hosted OAuth MCP service that connects AI clients to computers a user explicitly pairs to their account. The device runtime connects outbound; agents can inspect system information, manage files and processes, execute commands, and control supported browser and desktop interfaces. Unlike a documentation service, these tools can change the paired computer's state.

## Features

- File and directory management, terminal execution and process diagnostics on authorized paired devices.
- Native desktop and Chromium browser automation when the paired runtime supports the capability.
- Streamable HTTP remote MCP endpoint: `https://remcp.site/mcp`, with OAuth authentication.
- The host-side client/runtime is publicly available from the publisher.

## Connecting

Sign in to ReMCP, explicitly pair the computer, then add the hosted endpoint `https://remcp.site/mcp` to your MCP client and authorize its requested capabilities. Devices must be online.

## Security

Review permissions for state-changing tools before invoking them. Access is limited to devices paired by the authorized account; no permission-free remote execution is implied. See [official documentation](https://remcp.site/docs).
