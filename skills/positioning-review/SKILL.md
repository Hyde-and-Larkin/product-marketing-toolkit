---
name: positioning-review
description: "Review a homepage, pitch deck, launch doc, one-pager, or positioning statement the way a senior PMM would: score it on customer clarity, pain, differentiation, proof, and specificity, then return the top fixes with rewritten examples. Use for 'review our positioning', 'tear down this homepage', 'is this messaging any good', or as a QA gate on AI-written marketing copy."
---

# Positioning Review

> **Part of the [Product Marketing Toolkit](../../README.md).** If `context/positioning.md`, `context/icp.md`, and `context/competitors.md` exist, read them first and review the artifact against them. If they don't, review the artifact on its own terms and say so in the header.

AI makes it cheap to produce marketing copy. It doesn't make the copy say anything. This skill is the review step: does the thing actually tell a specific buyer why this product, over the alternatives, right now?

## What this produces

A Positioning Review with:

1. A one-paragraph verdict a busy founder or CMO can read in 20 seconds
2. Scores on six dimensions (see `rubric.md`), each with the evidence behind the score
3. The top 3 fixes, ranked by impact, each with a before/after rewrite
4. Questions only a human can answer (things the artifact can't settle)

Use the structure in `output-template.md`.

## Inputs

- The artifact (URL, pasted text, deck, doc)
- Who it's for (if not obvious, infer and label it as an assumption)
- What it's for (homepage, sales deck, launch post, investor pitch). The bar differs: a homepage has five seconds, a sales deck has a rep to explain it.

## Process

1. **Read it once as the buyer.** Before scoring anything, write down in one sentence what you think the product is, who it's for, and why you'd pick it. If you can't, that's the headline finding.
2. **Try the swap test.** Replace the company name with a competitor's. If the copy still works, the positioning isn't differentiated. Note the exact lines that survive the swap.
3. **Score each dimension in `rubric.md`.** Quote the specific line that drove each score. No score without evidence.
4. **Find the claims.** List every claim the artifact makes and whether it has proof attached. For a deep pass, hand the list to the `claims-proof-audit` skill.
5. **Rank fixes by impact, not by count.** A vague headline beats ten weak bullet points. Three fixes, maximum.
6. **Rewrite, don't just critique.** Each fix gets a before/after. Rewrites must use only facts present in the artifact or `context/`. Where a rewrite needs a fact you don't have, use a bracketed placeholder: `[the number of hours saved, from customer data]`.

## Guardrails

- Don't invent proof to make a rewrite land. A placeholder is better than a fake stat.
- Don't grade on writing style alone. Pretty copy that names no customer and no pain is still a 1.
- Separate taste from judgment. If a note is preference ("I'd cut the em dashes"), label it as minor and keep it out of the top 3.
- Be direct. The person asked for a review, not reassurance.

## Files

- `rubric.md`: the six dimensions and what each score means
- `output-template.md`: the review structure
