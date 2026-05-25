> 🧬 [aikdna.com](https://aikdna.com) — Official website

# @aikdna/content_strategy

[![KDNA Spec](https://img.shields.io/badge/KDNA-v1.0--rc-4c1)](https://github.com/aikdna/KDNA)

**Content strategy judgment** — evaluate whether a topic is worth writing based on specific audience, cognitive contrast, discussability, and comprehension barrier.

## What this KDNA changes

**Before loading this KDNA, an agent tends to:**
- Generate topic ideas without evaluating worthiness
- Treat all ideas as equally valid content candidates

**After loading this KDNA, an agent will judge:**
- Is there a specific audience with a real pain point?
- Does this topic create cognitive contrast?
- Is the topic discussable?
- Is the comprehension barrier low enough?

## This KDNA is for

- Topic evaluation and content strategy
- Filtering ideas by audience specificity and cognitive contrast
- Determining whether a topic is worth writing

## This KDNA is not for

- Topic generation in bulk
- Content calendars, SEO keyword planning
- Social media scheduling or trend scraping

## Core judgment

Ideas are cheap. Worthiness is rare. Filter topics by who they are for and what assumption they challenge.

## Self-checks

- Is there a specific audience, not "everyone"?
- Does this topic create cognitive contrast?
- Is the comprehension barrier low enough for the intended reader?
- Can the reader discuss this after reading?

## Install

```bash
kdna install @aikdna/content_strategy
kdna validate .
```

## Files

- `KDNA_Core.json` — Axioms, ontology, frameworks, causal structure, stances
- `KDNA_Patterns.json` — Terminology, banned terms, misunderstandings, self-checks
- `KDNA_Scenarios.json` — Scenario signals that shift strategy
- `KDNA_Cases.json` — Concrete cases showing judgment structure
- `KDNA_Reasoning.json` — Reasoning chains: conclusion → logic → action
- `KDNA_Evolution.json` — Capability stages, measurable indicators, growth paths
- `evals/` — Evaluation cases (quality: untested)
- `kdna.json` — Domain manifest

## License

CC BY 4.0
