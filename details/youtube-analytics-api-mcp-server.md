# YouTube Analytics API MCP Server

**Category:** Data Analysis & Exploration MCP Servers  
**Brand:** YouTube  
**Slug:** youtube-analytics-api-mcp-server

An MCP server that integrates the YouTube Analytics and Reporting APIs into MCP-compatible tools, enabling retrieval of YouTube analytics data for automated reporting and custom dashboards.

---

## Features

- **MCP Server Endpoint**  
  - Static server URL: `https://mcp.pipedream.net/v2`  
  - Single URL works for all MCP clients; authentication occurs when adding the server to the application.

- **YouTube Analytics & Reporting Integration**  
  - Connects to YouTube Reporting and YouTube Analytics APIs.  
  - Supports retrieval of analytics data for channels and videos.  
  - Designed for automating complex reporting tasks and building custom dashboards.

- **Available Tools / Actions**  
  1. **Query Custom Analytics**  
     - Execute custom analytics queries.  
     - Configurable with:  
       - Metrics  
       - Dimensions  
       - Filters  
       - Date ranges  
     - Uses YouTube Analytics reporting capabilities for flexible, ad‑hoc analysis.

  2. **List Channel Reports**  
     - Fetch summary analytics reports for a specified YouTube channel.  
     - Optional filters:  
       - Date range  
       - Report type (e.g., specific report categories supported by YouTube Reporting).  
     - Useful for channel‑level performance overviews.

  3. **Get Video Metrics**  
     - Retrieve detailed analytics for a specific video.  
     - Focused on per‑video performance metrics (e.g., views, watch time, engagement, subject to API capabilities).

- **Client-Agnostic Usage**  
  - Can be added to different MCP‑compatible chat or development clients.  
  - Configuration instructions available via a central configuration page (outside this summary).

---

## Pricing

No pricing information is provided in the available content.

---

## Tags

- analytics  
- reporting  
- youtube

---

## Links

- Source / App URL: https://mcp.pipedream.com/app/youtube_analytics_api  
- MCP Server URL: `https://mcp.pipedream.net/v2`  
- Action Documentation:
  - Query Custom Analytics: https://github.com/PipedreamHQ/pipedream/blob/master/components/youtube_analytics_api/actions/query-custom-analytics/query-custom-analytics.mjs  
  - List Channel Reports: https://github.com/PipedreamHQ/pipedream/blob/master/components/youtube_analytics_api/actions/list-channel-reports/list-channel-reports.mjs  
  - Get Video Metrics: https://github.com/PipedreamHQ/pipedream/blob/master/components/youtube_analytics_api/actions/get-video-metrics/get-video-metrics.mjs

---

## Media

- Brand logo: https://www.youtube.com/s/desktop/fe3e7345/img/favicon_144x144.png  
- Additional image: https://www.gstatic.com/youtube/img/branding/youtubelogo/svg/youtubelogo.svg