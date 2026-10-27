---
name: claims-proof-audit
description: "Audit every claim in a piece of marketing or sales content: extract the claims, classify them, check each against the proof library and a validation checklist, and return a ship / fix / cut verdict per claim with what evidence is missing. Use before publishing AI-written copy, launch materials, case studies, decks, or anything with numbers in it."
---

# Claims + Proof Audit

> **Part of the [Product Marketing Toolkit](../../README.md).** Read `context/proof-library.md` first. It's the list of claims your team can back up, with sources. Anything not in it is unproven until someone shows otherwise.

The most common weakness in AI-generated go-to-market work isn't tone. It's claims: vague benefits, numbers with no source, "industry-leading" with nothing behind it, and stats the model made up because the sentence wanted one. This skill finds them before a customer, a competitor, or a lawyer does.

## What this produces

A claims table with one row per claim:

| # | Claim (verbatim) | Type | Proof found | Status | Fix |
|---|---|---|---|---|---|

Plus a short summary: how many claims ship as-is, need a fix, or should be cut, and the single riskiest claim in the piece.

## Process

1. **Extract every claim.** A claim is any statement a skeptical buyer could ask "says who?" about. That includes numbers, comparisons ("faster than"), superlatives ("leading," "only"), outcomes ("cuts churn"), and customer stories.
2. **Classify each claim** using the types below.
3. **Look for proof** in this order: `context/proof-library.md`, material the user supplied, then public sources. Record where it came from.
4. **Run the checklist** (below) against each claim that has proof.
5. **Assign a status:**
   - **Ship:** proof exists, is current, and matches the claim as written
   - **Fix:** proof exists but the claim overstates it, or it's missing a timeframe, sample, or qualifier. Give the corrected wording.
   - **Needs proof:** plausible, but nothing backs it yet. Say exactly what evidence would.
   - **Cut:** can't be supported, or is a superlative/comparison that creates legal or credibility risk
6. **Flag suspected fabrications** separately. A suspiciously precise number with no source anywhere ("37% faster") in AI-drafted copy should be treated as invented until someone produces the source.

## Claim types

- **Performance:** speed, accuracy, uptime, time saved
- **Outcome:** revenue, cost, retention, conversion results for customers
- **Comparison:** vs. a named competitor, vs. "alternatives," vs. the old way
- **Superlative:** best, only, first, leading, #1
- **Social proof:** customer counts, logos, quotes, case studies, ratings
- **Mechanism:** how the product works ("syncs in real time")

## Validation checklist

For each claim with proof:

- [ ] Source is documented and someone could find it again
- [ ] Sample size is stated and reasonable for the claim (a single customer is an anecdote, not "customers see")
- [ ] Time period is stated and the data isn't stale (over 12 months: flag)
- [ ] The metric definition matches how it's used (an "active user" in the claim means the same thing as in the source)
- [ ] The claim says what the data says, not more ("up to" vs. "average"; "in a pilot" vs. "customers")
- [ ] Comparisons name what they compare against, and the comparison is fair
- [ ] Customer names and quotes have permission
- [ ] Anything regulated (health, finance, security, legal) has been through review

## Guardrails

- Never fill a gap with a made-up number. Replace with `[sourced metric, n, date]` and say what's needed.
- "Up to" is not a fix for an average you don't have.
- Mechanism claims are the easiest to prove and the most underused. If an outcome claim can't be backed, suggest the mechanism behind it instead.
- One strong, proven claim beats five soft ones. Recommend cutting before stacking.
