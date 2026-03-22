# AGENTS.md

## Purpose

This repository tracks business- and capability-focused intelligence from Techmeme.

The goal is not to summarize news for its own sake. The goal is to identify implications that matter for:
- markets and macro-sensitive sectors
- industry structure and competition
- investment watchlists
- startup opportunities
- product strategy

## Core files

- Daily notes: `notes/daily/`
- Durable synthesis: `notes/synthesized_implications.md`

## System

This repository has two layers:

1. **Daily notes**
   - additive
   - closer to the news flow
   - capture changes that matter for capability / technology, strategy / markets, or downstream ideas

2. **Synthesized implications**
   - slower-moving
   - capture only durable, higher-signal implications
   - should change only when repeated evidence or a clearly material development justifies it

Daily notes should inform the synthesis. The synthesis should inform how daily items are classified.

If `notes/synthesized_implications.md` does not yet exist or is materially thin:
- compare primarily against recent daily notes
- use `Watch` more often
- avoid pretending a durable synthesis already exists

## Core judgment rules

- Prioritize signal over completeness.
- Prefer fewer, sharper bullets over broad coverage.
- Omit items that do not change the strategic picture.
- Do not infer a durable industry shift from a single company datapoint unless it is clearly a step-change event.
- When uncertain, downgrade to `Watch`.
- Mixed evidence should remain mixed.
- Do not force a coherent narrative when the evidence is contradictory.
- Do not force a startup, product, or market implication unless it is reasonably supported.
- Important but not yet interpretable developments are allowed. Capture them as `Watch` bullets instead of forcing a stronger read than the evidence supports.

## Style

Write like a smart operator explaining the news to another smart operator.

Requirements:
- Use plain English.
- Prefer short sentences.
- Prefer concrete nouns and verbs over abstract nouns.
- Be concise without becoming cryptic.
- Be analytical without sounding like a memo or slide deck.
- Do not use hype.
- Do not use consultant, VC, or strategy jargon unless it is clearly the simplest term.
- If a sentence sounds impressive but not natural, rewrite it more simply.

Avoid phrases like:
- "value accrues"
- "workflow-native"
- "control point"
- "moat formation"
- "compression risk"
- "narrative support"
- "machine-readable execution"
- "relationship-bearing judgment"
- "surface area"
- "opening salvo"

Prefer:
- "who owns the workflow" over "workflow control"
- "can actually do the work" over "permission to act"
- "investors seem to want" over "public markets are demanding proof"
- "this suggests" over "what it may imply is"

Before writing each section, ask:
- What is the simplest way to say this?
- Would a smart reader say this out loud in conversation?
- Can I replace an abstract noun with a concrete verb?
- Can I cut this sentence by 30% without losing meaning?

## Daily notes

For each meaningful bullet, use one short inline signal label at the end:
- `[New]`
- `[Reinforcing]`
- `[Challenging]`
- `[Watch]`

Determine labels by comparing today’s developments against:
- recent daily notes
- active implications
- watchlist implications
- recorded disconfirming evidence in the synthesis

### Label guidance

- Use `[New]` when a development introduces a genuinely new implication and is strong enough that the synthesis should likely be updated now.
- Use `[Reinforcing]` when a development supports an existing implication without changing the basic shape of the view.
- Use `[Challenging]` when a development pushes against an existing implication or prior read, whether mildly or directly.
- Use `[Watch]` when a development looks important but is still too early, ambiguous, or underdetermined to interpret confidently.

`[Watch]` is the default home for:
- emerging themes
- one-off but notable signals
- developments that may matter if they repeat
- important facts whose readthrough is not yet clear

`[New]` should be used sparingly.
It does not mean merely novel.
It means new and important enough to justify a synthesis-level update.

### Daily note structure

~~~md
## YYYY-MM-DD

### Capability / technology shifts
- ...

### Strategic / market implications
- ...

### Implied ideas

#### Higher-conviction ideas

##### Investment watchlist ideas
- ...

##### Startup ideas
- ...

##### Product ideas
- ...

#### Speculative ideas worth tracking

##### Investment watchlist ideas
- ...

##### Startup ideas
- ...

##### Product ideas
- ...
~~~

### Daily note guidance

Do not include a separate "Major developments" section.

Only include items that lead to at least one of:
- a capability / technology shift
- a strategic / market implication
- a meaningful implied idea
- a `Watch` item that looks important but is not yet interpretable

If a news item does not change the picture in one of those ways, omit it.

Each bullet should usually answer:
- what happened
- why it matters
- what it may imply

But do not present these as explicit labeled sections or as a rigid three-part formula.

Write each bullet as a natural observation in plain English.

In most cases:
- sentence 1 = the concrete development or observed fact
- sentence 2 = the so-what

Include the implication only when it adds something non-obvious and reasonably supported.

Do not force all three elements into every bullet.

Every bullet should still begin with the concrete development or observed fact, even if it is filed under capability / technology shifts or strategic / market implications.

Do not lead with an abstract conclusion if you can anchor it in a specific observed development.

Prefer:
- "AWS plans to offer Cerebras inference alongside Trainium. This suggests inference is becoming more workload-specific."
over:
- "Inference is becoming more workload-specific."

Capability / technology shifts:
- changes in what systems can do
- changes in models, products, infrastructure, tooling, interfaces, deployment, or technical economics
- keep these grounded in concrete developments, not abstract trend language

Strategic / market implications:
- company strategy
- monetization
- competition
- pricing
- workflow ownership
- distribution
- cost structure
- industry structure
- cross-company or sector-level readthroughs

Do not split company-level and industry-level implications into separate sections.
Use one section and write the clearest level of analysis for the point.

When a development seems important but the readthrough is still unclear:
- include it as a `Watch` bullet
- state the concrete development
- briefly note why it may matter
- avoid forcing a stronger interpretation than the evidence supports

## Better idea generation

The goal is not to generate the first obvious adjacent idea. The goal is to generate a small number of ideas that are non-obvious, plausible, and valuable.

When producing startup or product ideas:
- Prefer real bottlenecks, painful new constraints, enabling layers, pricing shifts, and distribution changes.
- Avoid generic wrappers, generic copilots, and "AI for X" ideas unless there is a specific reason they are newly attractive.
- Ask:
  - What valuable problem becomes newly solvable?
  - What bottleneck becomes more painful?
  - Where is the real friction?
  - What does the consensus miss?

Evaluate candidate ideas on:
- plausibility
- non-obviousness
- value
- specificity
- distinctness

Only include ideas that are strong on at least 3 of those dimensions.

For each idea, briefly state:
- the problem
- who has it
- why now
- why it is not obvious
- what it depends on

When in doubt, prefer ideas built around bottlenecks, workflow failure modes, or changes in buyer behavior rather than novelty for its own sake.

## Synthesis

Do not mirror the daily notes. Update the synthesis only when there is durable evidence, repeated support, or a clearly material development.

The synthesis should follow the same tone rules as the daily notes:
- plain English
- direct
- concise
- specific
- no jargon for its own sake

But unlike the daily notes, the synthesis should make the framework more explicit.

For each active implication, maintain:
- title
- status
- confidence
- time horizon
- what is happening
- why it matters
- evidence base
- contradictory / disconfirming evidence
- potential implications
- contrarian view
- what would change the view

### Synthesis writing guidance

- Titles should be understandable on first read.
- Prefer direct titles over thesis-style or conference-slide titles.
- Prefer "X is happening" over "X is bifurcating" or "value is moving."
- Keep each section clear and concrete.
- Do not use the synthesis to sound smarter than the evidence.
- Keep the "so what" explicit, but write it in normal language.
- Use examples to make points concrete, not to overstate certainty.

### Evidence discipline

- `Contradictory / disconfirming evidence` must contain actual observed facts or outcomes that cut against the thesis.
- Do not place hypothetical objections there.
- If no disconfirming evidence exists yet, say so explicitly.
- `Contrarian view` should contain the strongest reasonable opposing interpretation.

### Tangible examples

In `Potential implications`, include illustrative company, product, or category examples when they make the point more concrete. Use examples to clarify the implication, not to overstate certainty.

## Lookback windows for synthesis

Use different evidence windows for different synthesis tasks.

### Default windows

- **New implication promotion:** prioritize the last **2–4 weeks** of daily notes
- **Updating existing implications:** prioritize the last **6–12 weeks** of daily notes
- **Long-term memory:** use the full `notes/synthesized_implications.md` document as the durable record of prior views

### How to apply these windows

- When deciding whether to create or promote a **new implication**, focus mainly on whether a theme appears repeatedly and meaningfully within the last **2–4 weeks**
- When deciding whether to **strengthen, weaken, or materially challenge** an existing implication, consider the last **6–12 weeks** of daily notes, along with the current synthesis entry
- When adding **contradictory / disconfirming evidence**, recent evidence may be enough if it is a real observed fact that clearly cuts against an existing implication

### Promotion rule

A new theme should usually be promoted into an active implication only when:
- it appears meaningfully on at least **3 separate days within roughly 2–4 weeks**, or
- a single development is clearly a **step-change event** with durable strategic significance

### Search discipline

- Do not scan the entire daily-note history indiscriminately for every synthesis run.
- Avoid stitching together sparse mentions across distant periods and calling them a durable trend.
- Use recent daily notes to assess what is happening now.
- Use the synthesis document to preserve longer-term memory of prior views.

### Practical default

Unless there is a reason to go further back, a synthesis run should usually review:
- the current monthly daily file
- the prior monthly daily file if needed
- the full `notes/synthesized_implications.md` document

## Ideas

Separate ideas into:
- **Higher-conviction ideas**
- **Speculative ideas worth tracking**

Rules:
- Higher-conviction ideas should be closely tied to observed developments.
- Speculative ideas are optional.
- Speculative ideas must be explicitly labeled and tied to an observed development.
- A speculative idea should usually be only one or two inferential steps beyond the evidence.
- If a speculative idea is weak or generic, omit it.

## Hard caps

These are ceilings, not targets. Empty sections are allowed.

Per daily entry:
- Capability / technology shifts: max 4
- Strategic / market implications: max 5

Ideas:
- Higher-conviction investment ideas: max 2
- Higher-conviction startup ideas: max 2
- Higher-conviction product ideas: max 2
- Speculative investment ideas: max 1
- Speculative startup ideas: max 1
- Speculative product ideas: max 1

## Writing examples

Bad:
- The equity market may punish AI credibility gaps faster than it rewards generic exposure.

Better:
- Investors seem quicker to punish weak AI stories than to reward vague AI positioning.

Bad:
- The application moat is moving away from raw model quality and toward workflow control, proprietary context, and permission to act.

Better:
- Better models alone are not enough. The winners are more likely to be products that already own the workflow, hold useful data, and can actually do things on the user’s behalf.

Bad:
- Premium closed-model vendors may gain pricing and partnership leverage faster than expected.

Better:
- If more labs stumble, the top closed-model vendors could get more pricing power and better partnership terms.

Bad:
- Prioritize task-native outputs such as visuals, guided flows, and action-ready summaries.

Better:
- Build features that return something usable, like a chart, a step-by-step flow, or a draft the user can act on.

## Change management

At the end of each run, provide a short changelog stating:
- what was added
- whether the synthesis changed
- what was strengthened, challenged, promoted, or left unchanged
- any notable uncertainty

## Monthly file rollover for daily notes

Daily notes are stored in one file per calendar month in `notes/daily/`, using the filename format: `YYYY-MM.md`

When updating daily notes:
- determine today's date first
- use the file for the current calendar month
- if that file does not exist, create it
- if creating a new monthly file, initialize it with a top-level title: `# YYYY-MM Daily Notes`
- then append the new dated entry under that file

Never append a new month's dated entries to the prior month's file.