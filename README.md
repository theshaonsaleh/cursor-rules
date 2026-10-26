# Cursor Rules

Reusable Cursor rules for any account or device.

## What’s included

| File | Use for |
|------|---------|
| [`user-rules.md`](user-rules.md) | Paste into **Cursor Settings → Rules → User Rules** (all chats) |
| [`rules/prompt-feedback.mdc`](rules/prompt-feedback.mdc) | Copy into a project’s `.cursor/rules/` folder |

## Setup on another account or device

### Option A — User Rules (all projects)

1. Open this file: [`user-rules.md`](user-rules.md)
2. Copy the rule block
3. In Cursor: **Settings → Rules → User Rules**
4. Paste and save

Same Cursor account syncs User Rules in the cloud. Different accounts need this paste once each.

### Option B — Project Rules (one repo)

1. Copy `rules/prompt-feedback.mdc` into that project:

```text
your-project/.cursor/rules/prompt-feedback.mdc
```

2. Commit it so every clone gets the rule.

## Syncing updates

After you change rules here:

1. `git pull` on each machine
2. If you use User Rules, re-copy from `user-rules.md` into Settings (project `.mdc` files update automatically on pull)
