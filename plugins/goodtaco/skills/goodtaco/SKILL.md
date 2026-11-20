---
name: goodtaco
description: Build, change, check and publish GoodTaco apps (business apps such as trackers, forms, dashboards and everyday tools for small businesses) with the GoodTaco tools. Use whenever the person mentions GoodTaco or asks to make, change, fix or publish one of their GoodTaco apps or its data.
---

# GoodTaco

GoodTaco hosts business apps for small businesses: trackers, forms, dashboards and the everyday tools a team uses.
You build the app yourself with the GoodTaco tools, on the person's own Claude or Codex subscription. GoodTaco
stores, compiles and hosts the app and runs no AI of its own.

## Start with the build guide

Before you create or change an app, call `get_build_guide` with the topic `workflow`, then read the other topics it
names (such as `app`, `routes`, `handlers` and `database`) when the work needs them. Follow it: it is how GoodTaco
apps are built, and it changes with the platform, so read it in each conversation instead of working from memory.

Get an app's `app_id` from `list_apps`, `get_app` or `create_app`. Never guess one.

## Signing in

GoodTaco needs a one-time sign-in before its tools work. If the GoodTaco tools aren't available yet, or a call says
to sign in, tell the person in plain words that GoodTaco needs them to sign in once, and how:

- In the Claude desktop app: open this plugin's GoodTaco connector and click **Connect**.
- In Claude Code: type `/mcp`, choose GoodTaco and pick **Authenticate**.
- In Codex: it asks them to sign in the first time GoodTaco is used.

They sign in to GoodTaco in their browser, pick a workspace and click **Connect**. Never ask them to paste a token,
key or password into the chat, and never say GoodTaco is connected until its tools answer.

If two GoodTaco servers are available (the person also added the GoodTaco connector by hand), use either one. They
are the same service and see the same apps.

## Working with the person

- Do the work with the tools. Never send the person to the GoodTaco console for something the tools can do
  (creating an app, adding a database or tables, building, checking the app, publishing, going back to an earlier
  version).
- Connecting an outside account such as Google, Gmail or QuickBooks needs the person's own sign-in, so ask them to
  connect it in GoodTaco.
- Share the preview link once you have checked the app works. Publish only when the person asks.
- Say what the app does and what changed in plain words, not file paths or code.
