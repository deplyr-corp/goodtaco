# GoodTaco for Claude and Codex

Build, preview and publish [GoodTaco](https://goodtaco.ai) apps with your own Claude or Codex subscription. Your AI
builds the app; GoodTaco compiles it, hosts it on a preview link and publishes it when you say so. Nothing is installed
or built on your computer.

## Install

**Claude desktop app:** Customize → Plugins → Add marketplace → enter `deplyr-corp/goodtaco` → install **GoodTaco**.

**Claude Code:**

```
/plugin marketplace add deplyr-corp/goodtaco
/plugin install goodtaco@goodtaco
```

**Codex:** add this repository as a plugin marketplace and install `goodtaco`.

The first time you use it, sign in to GoodTaco in your browser, pick your workspace and click **Allow**.

Prefer plain Claude (web, desktop or phone)? Add GoodTaco from Claude's connector list instead; it's the same service.

Help: https://goodtaco.ai/claude · Support: hello@goodtaco.ai · Privacy: https://goodtaco.ai/privacy-policy

This repository is generated from GoodTaco's main codebase (`app/scripts/build-goodtaco-plugin.mjs`); changes made
here directly are overwritten.
