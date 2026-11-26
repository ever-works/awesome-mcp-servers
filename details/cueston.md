# Cueston

Cueston is in-app guidance for SaaS web apps. Its hosted MCP server lets an AI assistant build, preview and publish product tours, tooltips, banners, onboarding checklists, surveys and announcements on your own app, then read how they perform.

## Connection

- Hosted endpoint: `https://app.cueston.com/api/mcp`
- Transport: Streamable HTTP
- Authentication: OAuth 2.1 with PKCE and dynamic client registration; you choose read, write or publish access on the consent screen. A Cueston account is required (free plan available).
- Local stdio bridge: `npx -y cueston mcp` (npm package `cueston`; run `npx cueston login` once or set `CUESTON_API_KEY`)
- Setup documentation: https://cueston.com/docs/mcp
- MCP Registry: com.cueston/cueston
- Source (MIT): https://github.com/andreycretsu/cueston-mcp

## What it can do

76 tools and 5 prompts:

- Find pages, UI elements with verified selectors, tracked events and saved audiences in your real product
- Create tours, tooltips, banners, checklists, surveys and announcements as drafts, and group them into campaigns
- Validate a draft against the real page, estimate its audience and share a preview link on your own site
- Publish when you say so, request review where approval is required, unpublish or roll back to any version
- Read guide analytics, survey results, stuck points, product analytics and retention

Nothing goes live until it is published. Roles, plan limits, approval rules and the audit log apply as they do in the dashboard.
