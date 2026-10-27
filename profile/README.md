## QAmcp: a free, open-source tester for MCP servers

QAmcp connects to an MCP server the way Claude, Cursor or Codex would, and tells you in plain words what's broken: tools the AI can't understand, missing or contradicting safety labels, hidden instructions in descriptions, bad-input handling, secrets leaking in error messages, login (OAuth) setup, resources and prompts.

Every result is checked by code, never by an AI, and shows its evidence. By default it only runs tools labeled read-only.

- **Test a server in your browser, no signup:** [qamcp.dev](https://qamcp.dev)
- **In your terminal:** `npx qamcp-cli https://your-server/mcp`
- **On every pull request:** the GitHub Action `QAmcp/qamcp-cli@v0`
- **Before you install someone else's server:** `npx qamcp-cli <link> --before-install`

**The code:** [qamcp-cli](https://github.com/QAmcp/qamcp-cli) (MIT). The other repo, `qamcp.github.io`, is the website: the [directory of tested public servers](https://qamcp.dev/directory.html) and the monthly [State of MCP servers](https://qamcp.dev/state-of-mcp-2026-10.html) report.
