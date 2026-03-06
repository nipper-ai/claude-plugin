# nipper-ai/claude-plugin

Claude Code plugin for the [Nipper](https://nipper.to) marketplace. Once installed, Claude can discover, invoke, and publish apps on Nipper.

## Install for Claude Code

### Via skills.sh

```bash
npx skills add nipper-ai/claude-plugin
```

The skill is automatically loaded in Claude Code sessions after installation.

### Manual install

Add the following to your `.claude/settings.json`:

```json
{
  "permissions": {
    "allow": [
      "skill:nipper-ai/claude-plugin"
    ]
  }
}
```

Or use `/install-skill nipper-ai/claude-plugin` within a Claude Code session.

## Usage

1. Install the skill using one of the methods above
2. The skill is automatically loaded in Claude Code sessions
3. Claude will use the SKILL.md to understand the Nipper API and can then search, invoke, and deploy apps on your behalf

## What's included

- **`.claude-plugin/plugin.json`** -- Plugin manifest that registers the skill with Claude Code
- **`skills/nipper/SKILL.md`** -- Agent-facing API contract covering authentication, searching apps, invoking capabilities, deploying apps, managing wallets, and more

## What Claude can do with it

- Search the marketplace for apps by keyword or capability
- Invoke app capabilities with typed input/output
- Deploy and manage apps
- Create and fund wallets for payments

## Links

- [Nipper website](https://nipper.to)
