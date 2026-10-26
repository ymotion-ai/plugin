# Ymotion plugin

Make and edit videos with [Ymotion](https://ymotion.ai) from Codex or Claude Code: the Ymotion tools
(its MCP server, signed in with your Ymotion account) and a short skill on how to use them.

## Codex (ChatGPT desktop)

```bash
codex plugin marketplace add ymotion-ai/plugin
```

Then open the Plugins Directory in the ChatGPT desktop app, choose **Ymotion**, install it, and sign in
with your Ymotion account when asked.

## Claude Code

```text
/plugin marketplace add ymotion-ai/plugin
/plugin install ymotion@ymotion
```

Then run `/mcp`, choose **ymotion**, and sign in with your Ymotion account in the browser.

## ChatGPT and Claude on the web

Add Ymotion as a connector instead: Settings → Connectors → add a custom connector with the URL
`https://ymotion.ai/mcp`, then sign in.
