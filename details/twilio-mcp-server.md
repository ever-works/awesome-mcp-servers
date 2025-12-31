# Twilio MCP Server

**Category:** Messaging MCP Servers  
**Brand:** Twilio  
**Slug:** `twilio-mcp-server`

## Overview
Twilio MCP Server is an MCP-compatible server that exposes Twilio’s SMS, voice, and messaging APIs to MCP-based tools and chat clients. It enables building and orchestrating communication workflows (SMS, phone calls, verifications, transcripts, and media operations) through a unified MCP interface.

Server base URL (for MCP clients):
```text
https://mcp.pipedream.net/v2
```

## Features

### General
- MCP server that integrates Twilio’s SMS, voice, and messaging APIs into MCP-based applications.
- Works with multiple MCP chat clients via a single static server URL.
- Uses Twilio account authentication when adding the server to an application.
- Provides 16 Twilio actions exposed as MCP tools (listed below).

### Available Tools / Actions

1. **Send SMS Verification**
   - Send an SMS verification to a phone number.
   - Uses a configured Twilio verification service.

2. **Send Message**
   - Send an SMS text message.
   - Supports optional media files (MMS).

3. **Phone Number Lookup**
   - Lookup information about a phone number (e.g., carrier or other Twilio Lookup data exposed by the component).

4. **Make a Phone Call**
   - Initiate an outbound phone call.
   - Pass text, a URL, or an application reference that Twilio will use to handle call flow.

5. **List Transcripts**
   - Return a list of transcripts associated with the Twilio account (for supported Twilio transcription resources).

6. **List Messages**
   - Return a list of messages associated with the account.
   - Useful for querying recent or historical SMS/MMS activity.

7. **List Message Media**
   - Return a list of media files associated with a specific message.

8. **List Calls**
   - Return a list of calls associated with the account.

9. **Get Transcripts**
   - Retrieve full transcripts for specified transcript SIDs.

10. **Get Message**
    - Return detailed information about a specific message.

11. **Get Call**
    - Return the call resource/details for an individual call.

12. **Download Recording Media**
    - Download a recording media file (e.g., call recordings) from Twilio.

13. **Delete Message**
    - Delete a message record from the account (where Twilio allows deletion).

14. **Delete Call**
    - Remove a call record from the account (where Twilio allows deletion).

15. **Create Verification Service**
    - Create a Twilio verification service for managing SMS verifications.

16. **(Unnamed/Other Actions)**
    - The page references a total of 16 actions; the last entry is partially shown as **Create Verification Service**. Any additional actions beyond those listed explicitly would be other Twilio API operations exposed as MCP tools, but they are not fully visible in the provided content.

## Integration & Configuration
- Connect a Twilio account within the hosting environment (Pipedream-based MCP server).
- Use the static MCP server URL `https://mcp.pipedream.net/v2` when configuring your MCP client.
- Add the server in your chosen MCP-compatible chat client and authenticate with Twilio credentials.
- A separate configuration page (not included in the provided content) offers client-specific setup steps.

## Pricing
No pricing information is provided in the supplied content. Use of this MCP server will typically require:
- A Twilio account with usage-based pricing for SMS, voice, and other services, and
- Any applicable pricing from the platform hosting the MCP server (e.g., Pipedream/Workday), which is not detailed in the content.