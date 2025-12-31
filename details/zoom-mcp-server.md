## Zoom MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Zoom  
**Source:** https://mcp.pipedream.com/app/zoom

### Overview
Zoom MCP Server is an MCP-compatible server that exposes Zoom’s video, audio conferencing, chat, webinar, and phone APIs for use in automated workflows and integrations. It connects a Zoom account to MCP clients via a static server URL and authenticated access.

### Features

#### MCP Server & Configuration
- Static MCP server endpoint: `https://mcp.pipedream.net/v2`
- Works with multiple MCP-compatible chat clients
- Authentication performed when adding the server to your application
- Central configuration via the Pipedream Zoom app / configuration page

#### Meetings
- **Update Meeting**  
  - Modify an existing Zoom meeting’s details (e.g., topic, time, and other settings)
- **Get Meeting Details**  
  - Retrieve detailed information about a specific meeting
- **Get Meeting Transcript**  
  - Fetch the transcript of a meeting (for meetings with transcription enabled)
- **List Past Meeting Participants**  
  - Retrieve information on participants from a past meeting
- **Add Meeting Registrant**  
  - Register a participant for a meeting programmatically

#### Webinars
- **Update Webinar**  
  - Update a webinar’s topic, start time, and other configuration settings
- **Get Webinar Details**  
  - Get details of a scheduled webinar
- **Add Webinar Registrant**  
  - Register a participant for a webinar
- **List Webinar Participants Report**  
  - Retrieve detailed reports for each webinar attendee (for the last 6 months)
- **List Past Webinar Q&A**  
  - List Q&A for a specific past webinar, including questions from attendees and answers from hosts/panelists

#### Zoom Phone & Call Data
- **List User’s Call Logs**  
  - Retrieve a user’s Zoom Phone call logs
- **List Call Recordings**  
  - Get account-level call recordings

#### Chat & User Data
- **Send Chat Message**  
  - Send chat messages to an individual Zoom contact or to a channel of which you are a member
- **View User**  
  - View information about the authenticated Zoom user

> Note: The site indicates “18 actions available as tools”; only those explicitly listed above are detailed in the provided content.

### Integrations / Use Cases
- Automate meeting and webinar creation, updates, and registrant management from MCP-based agents or workflows
- Sync webinar attendance and Q&A into external CRMs or analytics tools
- Analyze meeting transcripts with other MCP tools (e.g., summarization, sentiment analysis)
- Pull call logs and recordings into compliance, reporting, or QA workflows
- Power chat-driven workflows that send Zoom messages from MCP clients

### Pricing
Pricing information for Zoom MCP Server is not provided in the available content.