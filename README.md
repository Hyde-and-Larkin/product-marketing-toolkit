# Product Marketing Toolkit

**Product marketing skills for AI agents.** For product marketers, founders, and anyone doing product marketing without the title.

Most marketing skill packs teach agents channel tactics: ads, SEO, email. This one teaches the judgment underneath them. Who it's for, why it's different, whether the claim is true, and whether the launch is ready. Plain Markdown files that work in Claude Code, Cursor, Codex, ChatGPT, or anything else that can read a folder.

> Agents will create more go-to-market work. Not necessarily better go-to-market work. These skills are the review step.

## What's inside

### Context (`context/`)

Fill-in templates for your product marketing source of truth: company, positioning, ICP and personas, voice, objections, proof library, competitors. Every skill reads these first, so your agent works from the same facts as your team. [Start here.](context/README.md)

### Skills (`skills/`)

| Skill | What it does |
|---|---|
| [`competitive-intel`](skills/competitive-intel/SKILL.md) | Sourced competitive brief. Every claim tagged by source tier and confidence; no unsourced synthesis passed off as fact. |
| [`positioning-review`](skills/positioning-review/SKILL.md) | Scores a homepage, deck, or positioning statement on six dimensions, runs the swap test, returns the top 3 fixes with rewrites. |
| [`claims-proof-audit`](skills/claims-proof-audit/SKILL.md) | Pulls every claim out of a piece of content and marks it ship, fix, needs proof, or cut. Catches invented stats in AI copy. |
| [`launch-readiness`](skills/launch-readiness/SKILL.md) | Launch tiers, a phased T-60 to T+30 plan, and a readiness checklist across messaging, enablement, support, and measurement. |
| [`sales-enablement`](skills/sales-enablement/SKILL.md) | Turns positioning into playbooks, one-pagers, talk tracks, FAQs, objection handling, and training, scaled to the launch tier. |
| [`messaging-framework`](skills/messaging-framework/SKILL.md) | Layered messaging from category to differentiation, pain-to-platform mapping, positioning statement, claims bank. |
| [`battlecard`](skills/battlecard/SKILL.md) | One-competitor sales battlecard: why we win, traps, objection handling, switcher plays. |
| [`discovery-questions`](skills/discovery-questions/SKILL.md) | SPIN-style discovery and trap-setting questions by segment, persona, and deal stage. |

### Playbooks (`playbooks/`)

Skills chained into real workflows: [launch a feature](playbooks/launch-a-feature.md) and [respond to a competitor](playbooks/competitive-response.md).

## Quick start

**Claude Code (as a plugin):**

```
/plugin marketplace add hyde-larkin/product-marketing-toolkit
/plugin install product-marketing-toolkit@product-marketing-toolkit
```

The plugin installs the skills, not your context. Copy this repo's `context/` folder into the project you work in, or ask Claude to create it from the templates, so the skills have something to read.

**Any agent that reads a folder (Claude Code, Cursor, Codex, Copilot):**

```
git clone https://github.com/hyde-larkin/product-marketing-toolkit.git
```

Open the folder in your tool and say: *"Read AGENTS.md, then run positioning-review on [our homepage URL]."*

**ChatGPT, Claude.ai, Gemini:** paste a skill's `SKILL.md` into a project's instructions, or upload it as a file, along with your filled-in `context/` files.

More detail in [docs/how-to-use.md](docs/how-to-use.md).

## Using it with a team

This is built for the setup where a marketing team keeps its AI knowledge in one shared repo:

1. Use this repo as a template and make a **private** copy for your team.
2. Fill in `context/` together. That's your shared source of truth.
3. Everyone points their AI tool at the same repo. When someone improves a skill or updates the positioning, everyone gets it on the next pull.
4. Every change has a history. When output starts sounding off, you can see what changed and roll it back.

Plain files, owned by you, readable by whichever AI tool you use next year.

## Principles

- **Context before skills.** A skill can't fix vague positioning. It just produces vague content faster.
- **No invented proof.** Skills use placeholders like `[sourced metric, n, date]` instead of making up numbers.
- **Findings and judgment stay separate.** Sourced facts, inferences, and recommendations are labeled differently.
- **Review, don't just generate.** The most useful thing an agent can do with marketing copy is tell you what's wrong with it.

## Status

v0.1. The skills are built from working product marketing practice; worked examples against real, public companies are coming next. Issues and pull requests welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## About

Built and maintained by [Hyde & Larkin](https://hydelarkin.com), from 15 years of B2B SaaS product marketing. Frameworks only: no employer or client confidential material is included.

Licensed under [CC BY 4.0](LICENSE.md). Use it, adapt it, sell work you make with it; just credit the source.
