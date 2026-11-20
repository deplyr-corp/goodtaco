# GoodTaco

Build, preview and publish GoodTaco apps with Claude or Codex. Sign in to GoodTaco once, then ask for an app: your AI builds it with your own subscription, GoodTaco compiles and hosts it on a preview link, and it goes live when you say so.

## Install

In the Claude desktop app: **Customize → Plugins → Add marketplace**, enter `deplyr-corp/goodtaco`, then install
**GoodTaco**. In Claude Code:

```
/plugin install goodtaco --marketplace deplyr-corp/goodtaco
```

## What you can ask for

- "Build me a GoodTaco app that tracks work orders for my crew."
- "Add a status column to my inventory app and put it on the preview link."
- "Publish my approvals app."

## How it works

Your Claude (or Codex) builds the app with your own subscription; GoodTaco compiles and hosts it. Nothing is
installed or built on your computer. The plugin uses the same GoodTaco service as the GoodTaco connector in Claude,
so an app you start in one carries on in the other.

## Signing in

The first time you use it, GoodTaco asks you to sign in once. In the Claude desktop app, open the plugin's GoodTaco
connector and click **Connect**; in Claude Code, type `/mcp`, choose GoodTaco and pick **Authenticate**; Codex asks
on first use. Sign in, pick your workspace and click **Allow**. You never paste a password or key into the chat.
You can remove access any time from your GoodTaco settings at https://console.goodtaco.ai.
