# GoodTaco for Claude, ChatGPT and Codex

Build, preview and publish [GoodTaco](https://goodtaco.ai) apps with your own Claude, ChatGPT or Codex plan. Your AI
builds the app; GoodTaco compiles it, hosts it on a preview link and publishes it when you say so. Nothing is installed
or built on your computer.

## Install

**Claude desktop app:** Customize → Plugins → Add marketplace → enter `deplyr-corp/goodtaco` → install **GoodTaco**.

**Claude Code:**

```
/plugin marketplace add deplyr-corp/goodtaco
/plugin install goodtaco@goodtaco
```

**Codex:**

```
codex plugin marketplace add deplyr-corp/goodtaco
codex plugin add goodtaco@goodtaco
```

The first time you use it, sign in to GoodTaco in your browser, pick your workspace and click **Connect**.

Prefer plain Claude or ChatGPT (web, desktop or phone)? Add GoodTaco from Claude's connectors or ChatGPT's plugins
instead; it's the same service and the same apps.

Help: https://goodtaco.ai/claude · https://goodtaco.ai/chatgpt · Support: hello@goodtaco.ai · Privacy:
https://goodtaco.ai/privacy-policy

`plugins/goodtaco` is the Claude plugin; `codex/goodtaco` is the same plugin as an Agent Plugins package for OpenAI
(Codex installs it, and it's the ChatGPT/Codex directory submission). This repository is generated from GoodTaco's main
codebase (`app/scripts/build-goodtaco-plugin.mjs`); changes made here directly are overwritten.

License: MIT.
