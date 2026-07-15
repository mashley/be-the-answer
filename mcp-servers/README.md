# MCP Servers

MCP ("connectors") let an AI like Claude use the tools of another app directly. The one that matters for
this workshop:

- **[Connect Radi8 to Claude](radi8-connector.md)** — step-by-step: let Claude read your brand, write
  on-brand content, and schedule posts for you, right from a chat.

## Add any MCP server to Claude
- **Claude.ai:** Settings → Connectors → *Add custom connector* → paste the server URL → authorize.
  (Custom connectors need a paid Claude plan.)
- **Claude Code (terminal):**
  ```bash
  claude mcp add --transport http <name> <url>     # HTTP server
  claude mcp add <name> -- <command to run it>     # local server
  ```

More: [Claude connectors & MCP docs](https://docs.claude.com/en/docs/claude-code).
