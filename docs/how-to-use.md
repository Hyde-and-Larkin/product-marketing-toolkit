# How to use the toolkit

You don't need to be technical. If you can download a folder, you can use this.

## 1. Get a copy

- **Just trying it:** click **Code → Download ZIP** on GitHub and unzip it.
- **Using it with a team:** click **Use this template** to make your own private repo. Teammates connect their AI tool to that repo, and everyone works from the same files.

## 2. Fill in `/context`

Start with `company.md`, `positioning.md`, and `icp.md`. Rough is fine. You can ask your agent to draft them from your website and a few call transcripts, then edit what it gets wrong.

## 3. Run a skill

### Claude Code

Install as a plugin:

```
/plugin marketplace add hyde-larkin/product-marketing-toolkit
/plugin install product-marketing-toolkit@product-marketing-toolkit
```

Or open the cloned folder in Claude Code. The `CLAUDE.md` file points it to the instructions. Then ask in plain language: *"Run a positioning review of our pricing page."*

### Cursor, Codex, GitHub Copilot, and other coding agents

Open the folder. These tools read `AGENTS.md` automatically or on request. Ask: *"Read AGENTS.md, then use the claims-proof-audit skill on launch-post.md."*

### ChatGPT, Claude.ai, Gemini (chat apps)

Create a project (or custom GPT / Gem). Add to its files or instructions:

1. The `SKILL.md` for the skill you want (plus any files in that skill's folder)
2. Your filled-in `/context` files

Then ask as normal.

## 4. Keep it current

- Update `/context` when positioning, pricing, or competitors change. Every skill picks up the change.
- If you use GitHub, every edit is saved with a note on who changed what. If outputs start going sideways, look at what changed in `/context` last.

## Good first runs

- *"Run positioning-review on [our homepage URL]."*
- *"Run claims-proof-audit on this draft"* (paste the draft).
- *"Run competitive-intel on [competitor]. We sell to [segment]."*
