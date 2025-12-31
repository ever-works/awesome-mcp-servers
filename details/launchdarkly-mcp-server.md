# LaunchDarkly MCP Server

**Category:** Development Tools / MCP Servers  
**Brand:** LaunchDarkly  
**Slug:** `launchdarkly-mcp-server`

An OAuth-enabled MCP (Model Context Protocol) server that connects to LaunchDarkly’s feature management and experimentation platform. It exposes LaunchDarkly operations (like managing feature flags and projects) as tools that can be used from MCP-compatible chat clients and applications.

![LaunchDarkly](https://launchdarkly.com/static/brand/launchdarkly-logo-tagline.svg)

---

## Features

### Secure OAuth-based access
- Connects to LaunchDarkly using OAuth for authenticated access.  
- Uses a static MCP server URL for all clients:
  - `https://mcp.pipedream.net/v2`
- Authentication occurs when adding the server to an MCP-compatible application.

### MCP server integration
- Designed for use via the Model Context Protocol (MCP) with chat clients and other MCP-enabled tools.
- Can be added to supported clients by specifying the MCP server URL and completing OAuth sign-in.

### Available tools (actions)
The server exposes LaunchDarkly functionality as tools/actions:

1. **Update Feature Flag**  
   - Update an existing feature flag using a JSON object.

2. **Toggle Feature Flag**  
   - Toggle a feature flag’s status between active and inactive.

3. **List Projects**  
   - Retrieve a list of all projects in the LaunchDarkly account.

4. **List Members**  
   - List all members (users) associated with the LaunchDarkly account.

5. **List Feature Flags**  
   - List all feature flags within the account.

6. **List Environments**  
   - List all environments configured in LaunchDarkly.

7. **Get Project**  
   - Retrieve a single project by its key.

8. **Get Feature Flag**  
   - Retrieve a specific feature flag by its key.

9. **Get Feature Flag Status**  
   - Get the current status of a specific feature flag.

10. **Evaluate Feature Flag**  
    - Evaluate an existing feature flag for a specific user or general context.

---

## Technical details
- **Protocol:** Model Context Protocol (MCP)
- **Auth method:** OAuth (account sign-in required)  
- **Base MCP server URL:** `https://mcp.pipedream.net/v2`

---

## Pricing
Pricing details are not provided in the available content. Users should refer to Pipedream or LaunchDarkly pricing pages for cost information related to usage of this MCP server and the underlying LaunchDarkly account.

---

## Tags
- Feature flags  
- Experimentation  
- DevOps
