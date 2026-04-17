# ConfigCat MCP Server

Official MCP server for [ConfigCat](https://configcat.com/), a feature flag and configuration management service. It exposes the full [ConfigCat Public Management API](https://configcat.com/docs/api/reference/configcat-public-management-api/) as MCP tools, enabling AI agents to manage feature flags, targeting rules, environments, segments, user permissions and more — directly from any MCP-compatible AI client.

[https://github.com/configcat/mcp-server](https://github.com/configcat/mcp-server/)

## Features

### Feature Flag & Setting Management
- Create, read, update, and delete Feature Flags and Settings within Configs
- List all Feature Flags/Settings in a Config, or filter by Tag
- Get and set Feature Flag values per Environment, including default values and targeting rules
- Batch update Feature Flag values across a Config in a given Environment
- Support for boolean, string, integer, and double setting types
- Set initial values per Environment when creating a Feature Flag
- JSON Patch support for granular updates to flag metadata and values
- Detect stale (zombie) flags with configurable inactivity thresholds
- Retrieve code references for Feature Flags

### Targeting & Percentage Rules
- Configure targeting rules based on user attributes (User ID, Email, Country, custom attributes)
- Support for 30+ comparators: text, semver, number, sensitive, date/time, array comparisons
- Segment-based targeting rules (is in / is not in segment)
- Prerequisite flag conditions
- Percentage-based rollouts with configurable evaluation attributes
- Ordered rule evaluation matching ConfigCat's evaluation logic

### Config Management
- Create, read, update, and delete Configs within Products
- Support for Config V2 evaluation version

### Environment Management
- Create, read, update, and delete Environments within Products
- Environment-specific feature flag values and targeting rules
- Color-coded environments for dashboard organization

### Product Management
- Create, read, update, and delete Products within Organizations
- Configure Product preferences: key generation mode, mandatory hints, reason-required settings
- Per-environment reason-required configuration

### Organization Management
- List Organizations the authenticated user belongs to

### Segment Management
- Create, read, update, and delete user Segments within Products
- Define segment rules with comparison attributes and operators
- Use segments in feature flag targeting rules

### Tag Management
- Create, read, update, and delete Tags within Products
- Attach/detach Tags to Feature Flags and Settings
- Color-coded tags (panther, whale, salmon, lizard, canary, koala, or HTML color codes)

### Permission Group Management
- Create, read, update, and delete Permission Groups within Products
- Granular permission controls: manage members, configs, environments, settings, tags, webhooks, segments, integrations, SDK keys, audit logs, statistics, export/import, 2FA
- Environment-specific access levels (full, readOnly, none)

### Team Member Management
- Invite members to Products with specific Permission Groups
- List Organization and Product members
- Update member permissions and move between Permission Groups
- Remove members from Organizations or Products
- Manage pending invitations

### Webhook Management
- Create, read, update, and delete Webhooks per Config/Environment
- Support for GET and POST HTTP methods with custom headers and body content
- Secure header values for sensitive data
- Webhook signing keys for request verification
- JSON Patch support for partial webhook updates

### Audit Logs
- Query audit logs at the Product or Organization level
- Filter by Config, Environment, date range, and audit log event type
- 70+ audit log event types covering all management operations

## Configuration

The ConfigCat MCP server requires authentication via a ConfigCat Public Management API credential (basic auth with `username` and `password`). API credentials can be generated in the [ConfigCat Dashboard](https://app.configcat.com/my-account/public-api-credentials).

## Comparison

Unlike LaunchDarkly and Statsig, ConfigCat collects zero user data during feature flag evaluation, making it inherently GDPR-compliant and ideal for organizations with strict data privacy and compliance requirements.

## Pricing

ConfigCat offers a forever free tier and paid plans. See [configcat.com/#pricing](https://configcat.com/#pricing) for details.