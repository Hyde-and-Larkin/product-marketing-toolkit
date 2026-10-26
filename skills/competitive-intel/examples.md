# Examples: weak vs. strong output

So an agent, or a person reviewing agent output, can see the difference between a brief that's usable and one that just looks fine.

> **Status:** illustrative. The scenario and company below are fictional. A real worked example, run against public competitors, is coming in a future release.

## Scenario

A PMM at a mid-market project management SaaS company asks for a brief on a competitor called "Fictional Flow" ahead of a Q3 launch.

## Weak output (what to avoid)

> Fictional Flow is a strong competitor with good reviews. Users like the interface, and some people mention it's expensive. They seem to be moving upmarket. We should probably emphasize our pricing advantage.

What's wrong with it:

- No sources, no dates, no confidence ratings
- "Some people mention" treats an anecdote as a finding
- "Seem to be moving upmarket" is inference stated as fact
- No distinction between a pattern and a one-off
- The recommendation has no reasoning and doesn't tie back to a logged gap

## Strong output (same scenario, per the template)

> **Pricing sentiment** [Pattern: Tier 2, 4 independent G2 reviews, Jan-Jun 2026]: reviewers describe the jump from the mid tier to the top tier as steep relative to the features gained.
>
> **Roadmap signal** [Inference, based on 6 open engineering roles for enterprise SSO and audit logging as of Jun 2026]: possible move upmarket. Flagged as inference, not confirmed.
>
> **Trap tied to pricing gap:** "What happens to your monthly cost once you need [the gated feature]?" Tied to the corroborated pricing-tier gap above.
>
> **Recommendation:** lead with total cost at the tier where the gated feature lives, not the list price. Reasoning: the corroborated complaint is about the tier jump, not the entry price.

The difference isn't tone. It's traceability. Every claim in the strong version can be checked, and inference is labeled as inference.
