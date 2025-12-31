# Google Slides MCP Server

**Brand:** Google  
**Category:** Content Management MCP Servers  
**Tags:** presentations, google-workspace, collaboration

## Overview
The Google Slides MCP Server is an MCP (Model Context Protocol) server running on the Pipedream MCP platform that enables AI and applications to create, edit, and collaborate on Google Slides presentations. It exposes Google Slides operations as tools that can be called from compatible chat clients or AI agents via a static MCP endpoint.

- **MCP base URL:** `https://mcp.pipedream.net/v2`

## Integration & Setup
- Connect a Google account to authorize access to Google Slides and Drive.
- Use the static MCP server URL for all clients; authentication occurs when adding the server to your application.
- Add the server to supported chat clients or other MCP-compatible applications using the provided URL.

## Features

### General Capabilities
- AI-driven creation and editing of Google Slides presentations.
- Collaboration on existing presentations via automated actions.
- File access and search via Google Drive for locating presentations.

### Available Tools / Actions (17 total)
Below are the actions explicitly listed as available tools exposed by the server:

1. **Replace All Text**  
   - Replace all occurrences of specified text across a presentation.

2. **Refresh a Chart**  
   - Refresh a chart in Slides that is linked to Google Sheets data.

3. **Merge Data**  
   - Merge external or structured data into a presentation (e.g., templated slides populated from data sources).

4. **Insert Text**  
   - Insert text into a shape on a slide.

5. **Insert Text into Table**  
   - Insert text into a specific table cell within a slide.

6. **Insert Table Rows**  
   - Insert new rows into an existing table on a slide.

7. **Insert Table Columns**  
   - Insert new columns into an existing table on a slide.

8. **Find a Presentation**  
   - Search and locate a presentation stored in Google Drive.

9. **Delete Table Row**  
   - Delete a row from a table in a slide.

10. **Delete Table Column**  
    - Delete a column from a table in a slide.

11. **Delete Slide**  
    - Remove a slide from a presentation.

12. **Delete Page Element**  
    - Delete a specific page element (e.g., shape, image, text box) from a slide.

13. **Create Table**  
    - Create a new table on a slide.

14. **Create Slide**  
    - Create a new slide within an existing presentation.

15. **Create Presentation**  
    - Create a new blank presentation or duplicate an existing one.

16. **Create Page Element**  
    - Create a new page element on a slide (such as a shape or other supported element).  

17. **(Implicit)**  
    - The interface lists a total of 17 tools; the above are the ones explicitly named. The server exposes all 17 as MCP tools for use in compatible clients.

## Pricing
No pricing information is provided in the available content. Pricing, if any, would need to be obtained from Pipedream or Google’s official documentation.