# Pattern: AI Visibility Measurement

## Applicable Situation

Use when a team needs to measure how often a brand, product, source, or topic appears inside AI answers, AI Overviews, answer engines, or LLM-powered discovery flows.

## Inputs

- Target entity, product, category, or topic
- Query or question set
- Search and answer surfaces to test
- Competitors or alternative sources
- Existing analytics and referral data
- Citation, mention, conversion, or visibility goals

## Default Workflow

1. Define the visibility object: company, product, page, source, category, or topic.
2. Build a representative query set across awareness, comparison, evaluation, and purchase intent.
3. Separate citation, mention, ranking, answer inclusion, AI referral, and conversion metrics.
4. Capture the answer surface: Google AI Overview, ChatGPT, Perplexity, Copilot, Gemini, Claude, site search, or commerce assistant.
5. Record which sources are cited, which brands are mentioned, and whether the target entity is included accurately.
6. Compare against named competitors, publishers, marketplaces, and status quo sources.
7. Set a measurement cadence and track changes after content, schema, proof, or source updates.

## Branch Rules

- If clicks are falling but mentions are rising, treat zero-click visibility as a separate signal instead of a failed traffic metric.
- If AI referral traffic is small, use citations and mention share as leading indicators.
- If the surface does not expose citations, record answer inclusion and source inference separately.
- If the query set is unstable, freeze a baseline set before testing content changes.

## Anti-Patterns

- Measuring only website sessions when the discovery surface is zero-click.
- Treating one prompt result as a stable benchmark.
- Mixing branded, category, and competitor queries into one score.
- Optimizing for mentions without checking accuracy or source quality.

## Acceptance Criteria

- The query set represents real buyer or user questions.
- Citations, mentions, referrals, and conversions are reported separately.
- Results can be compared across time and surfaces.
- The report identifies next actions for content, schema, proof, or source coverage.

## Conflict Notes

Some sources frame AI referrals as the primary metric, while others emphasize visibility before click. Use referrals as an outcome metric and citations or mentions as leading indicators.

## Evidence Level

B
