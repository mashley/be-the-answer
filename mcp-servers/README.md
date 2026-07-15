# MCP Servers

Notes and links for the MCP (Model Context Protocol) servers referenced in the workshop — what each one does and how to connect it.

**Suggested table — fill in as you go:**

| Server | What it does | Link / install |
|---|---|---|
| _example_ | _one line_ | `https://…` |

## How participants add an MCP server to Claude Code

```bash
# HTTP/SSE server
claude mcp add --transport http <name> <url>

# local (stdio) server
claude mcp add <name> -- <command to run it>
```

More: [Claude Code MCP docs](https://docs.claude.com/en/docs/claude-code).
