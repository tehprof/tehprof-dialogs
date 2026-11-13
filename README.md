# TehProf Dialogs for Gemini

Work with your TehProf Dialogs inbox — WhatsApp, Telegram, MAX and phone calls, linked to Bitrix24 or amoCRM — from
Gemini CLI or Antigravity: who is waiting, whom to call back, draft replies, move deals. Every message to a customer
and every CRM change waits for your explicit yes.

You need a TehProf Dialogs account: https://dialogs.tehprof.kz

## Gemini CLI

```
gemini extensions install https://github.com/tehprof/tehprof-dialogs
```

Then type `/mcp auth tehprof-dialogs` and sign in. Without the extension the same server is one command:
`gemini mcp add --transport http tehprof-dialogs https://dialogs.tehprof.kz/mcp`.

## Antigravity

The Antigravity plugin is published as a separate repository: https://github.com/tehprof/tehprof-dialogs-antigravity. Install it and sign
in when Antigravity opens the browser.

## Other MCP clients

Any client that supports remote MCP servers with OAuth (Claude, ChatGPT, Cursor, VS Code, Cline, Kiro…) connects to
the same address: `https://dialogs.tehprof.kz/mcp` (Streamable HTTP, OAuth 2.1 with dynamic client registration).
The `.mcp.json` file in this repository is that configuration.

Help: https://dialogs.tehprof.kz/help/ai-assistants/ · Support: support@tehprof.kz
