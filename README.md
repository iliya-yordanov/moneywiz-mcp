# MoneyWiz MCP (Mac AI Connections)

The MoneyWiz app for Mac includes a local, read-only MCP server. This repository documents it; the server itself ships inside the app as a bundled stdio helper, is not open source, and has no remote endpoint.

I'm Iliya Yordanov, the creator of MoneyWiz.

## Setup

1. Open [MoneyWiz for Mac](https://apps.apple.com/app/id1511185140) (macOS 14 or later).
2. Go to Preferences > AI Connections.
3. Click Connect for Claude, Codex, or Cursor, or choose "Use another AI app…" and copy the command and arguments.

MoneyWiz must be open and unlocked. AI Connections requires a Standard or Premium plan.

## What it can read

The server can read the database currently open in MoneyWiz: accounts, balances, net worth, transactions, investments, budgets, scheduled transactions, and loans. It cannot change anything.

## Privacy

The connection runs on your Mac. Your AI app then sends what it reads to its own provider, under that provider's policy.

## Docs and support

- Setup guide: https://help.wiz.money/a/ai-connections-on-mac
- Product site: https://www.wiz.money
- Contact: hello@wiz.money
