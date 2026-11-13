# Installing TehProf Dialogs (for AI agents)

TehProf Dialogs is a hosted remote MCP server. Nothing needs to be cloned, built or installed.

1. Add this server to the MCP settings (for Cline: `cline_mcp_settings.json`):

```json
{
  "mcpServers": {
    "tehprof-dialogs": {
      "type": "streamableHttp",
      "url": "https://dialogs.tehprof.kz/mcp"
    }
  }
}
```

2. The server uses OAuth 2.1 with dynamic client registration. On first use the client opens the browser;
   the user signs in with their TehProf Dialogs account. No API key is needed.
3. Check the connection by calling the `day_summary` tool.

A TehProf Dialogs account is required: https://dialogs.tehprof.kz
