---
name: measure-ai-search-performance
description: Design AI search performance measurement across query sets, prompt sets, citations, mentions, AI referrals, AIO presence, competitor share, quality review, and benchmark cadence. Use when Codex needs to measure ChatGPT, Perplexity, Google AI Overviews, or other answer-engine visibility without treating traffic as the only success metric.
---

# Measure AI Search Performance

Use this skill to build a measurement system for AI search and answer-engine visibility. The goal is repeatable visibility learning, not a one-time prompt check.

## Owned Inputs

Measurement objective, query and prompt sets, answer surfaces, competitors, collection constraints, analytics, screenshots/exports, and benchmark cadence.

## Owned Outputs

AI search measurement plan, metrics, collection rules, baseline design, competitor/source tracking, reporting format, and refresh cadence.

## Shared References

- `references/shared/boundaries/aeo-seo.md`
- `references/shared/boundaries/cross-family.md`
- `references/shared/sources/source-policy.md`

## Hard Boundaries

- Own only this skill's task-triggered output.
- Use shared references instead of copying pattern logic into this skill.
- Hand off positioning problems to GTM, product fact gaps to Product, and content brief creation to build-aeo-content-brief.
- Read `references/source-map.md` and shared references only when provenance, boundary checks, or deeper pattern detail is needed.

## Workflow

1. Define the measurement objective: brand visibility, category presence, competitor comparison, content impact, launch monitoring, or conversion signal.
2. Build a stable query and prompt set across branded, non-branded, problem, comparison, and buying-intent questions.
3. Choose surfaces to measure: Google AI Overviews, ChatGPT, Perplexity, Copilot, Gemini, Claude, site search, commerce assistant, or analytics referral source.
4. Define metrics separately: citation, mention, answer inclusion, rank/order, accuracy, sentiment, AI referral traffic, conversion, and assisted pipeline.
5. Set collection rules for date, location, account state, prompt wording, screenshots/exports, source links, and competitor mentions.
6. Create a baseline and comparison cadence.
7. Connect measurement changes to content, schema, proof, source credibility, or launch updates.

## Boundary Rules

- Do not judge GTM success only from AI referral traffic; AI answers can influence zero-click discovery.
- Do not use one ad hoc prompt as a benchmark.
- If the metric exposes a positioning problem, hand off to GTM instead of rewriting positioning.
- If the metric exposes missing or unstable product facts, hand off to Product.
- If the measured surface is an agent or commerce assistant, measure visibility and factual accuracy only; do not design the agent integration.

## Output Format

- Measurement objective
- Query and prompt set
- Surface coverage
- Metric definitions
- Collection protocol
- Baseline table
- Review cadence
- Interpretation rules
- Action mapping
- Handoff notes

## When To Read References

- Read `references/source-map.md` for source provenance.
- Read these pattern cards when needed:
  - `references/shared/patterns/ai-visibility-measurement.md`
  - `references/shared/patterns/entity-source-credibility.md`
  - `references/shared/patterns/answer-ready-content.md`
  - `references/shared/patterns/growth-bottleneck-map.md`

## Quality Bar

- Metrics separate citations, mentions, traffic, and conversion.
- The query set can be rerun without changing the benchmark.
- Competitor and source visibility are captured, not just target-brand presence.
- The output explains what action each metric can trigger.
