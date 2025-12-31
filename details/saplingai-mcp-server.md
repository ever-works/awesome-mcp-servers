# Sapling.ai MCP Server

**Category:** AI Integration – MCP Servers  
**Brand:** Sapling.ai

An MCP server that connects MCP environments to Sapling.ai’s language models for writing assistance and communication, focused on grammar, spelling, style, and predictive text within enterprise applications.

---

## Features

### MCP Server & Connection
- Static MCP server endpoint: `https://mcp.pipedream.net/v2` (works for all clients).
- Authentication performed when adding the server to your application.
- Usable with multiple chat clients and MCP-compatible applications.
- Central configuration flow via “Configure Sapling.ai” and client selection.

### Language & Writing Assistance Tools
Five actions are exposed as tools within the MCP server:

1. **Request Edits**
   - Provides grammar, spelling, and stylistic edits for text.
   - Customizable with a user-defined dictionary.
   - Supports custom mappings for specialized terminology.
   - Supports custom language models (contact Sapling for setup).
   - Prebuilt models available for domain-specific use cases such as healthcare/medicine.

2. **Request Completion**
   - Generates predictions for the next characters or words based on the current text context.
   - Uses the preceding text in an editable field to suggest continuations.

3. **Reject Edit**
   - Sends feedback to Sapling that a specific edit suggestion was not helpful.
   - Uses an edit UUID associated with each suggested edit.
   - Helps prevent the same edit from being recommended again.

4. **Accept Edit**
   - Sends feedback that a specific edit suggestion was helpful.
   - Uses the edit UUID tied to the suggestion.
   - Enables Sapling to adapt its system over time based on accepted edits.

5. **Accept Completion**
   - Sends feedback that a specific completion suggestion was helpful.
   - Uses a completion UUID associated with each suggested completion.
   - Helps Sapling adapt its completion behavior over time.

### Adaptation & Feedback Loop
- Edit and completion feedback (accept/reject) used to refine future suggestions.
- Supports continuous improvement of writing assistance within enterprise workflows.

---

## Pricing

No pricing information is provided in the available content. Users should refer to Sapling.ai or Pipedream for current pricing details.