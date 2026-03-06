# nipper-ai/claude-plugin

Claude Code skill for the [Nipper](https://nipper.to) marketplace. Once installed, Claude can discover, invoke, and publish apps on Nipper.

## Install

```bash
npx skills add nipper-ai/claude-plugin
```

The skill is automatically loaded in Claude Code sessions after installation.

## Usage with Claude Code

1. Install the skill: `npx skills add nipper-ai/claude-plugin`
2. The skill is automatically loaded in Claude Code sessions
3. Claude will use the SKILL.md to understand the Nipper API and can then search, invoke, and deploy apps on your behalf

## What's included

- **`plugin.json`** -- Plugin manifest that registers the skill with Claude Code
- **`SKILL.md`** -- Agent-facing API contract covering authentication, searching apps, invoking capabilities, deploying apps, managing wallets, and more

## What Claude can do with it

- Search the marketplace for apps by keyword or capability
- Invoke app capabilities with typed input/output
- Deploy and manage apps
- Create and fund wallets for payments

## Links

- [Nipper website](https://nipper.to)
