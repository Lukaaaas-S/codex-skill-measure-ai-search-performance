# Pattern: Entity Source Credibility

## Applicable Situation

Use when a brand, product, person, company, or source needs to be credible enough for search engines, answer engines, and LLM systems to cite or recommend it.

## Inputs

- Target entity and official pages
- Product or company facts
- Third-party sources and citations
- Reviews, comparisons, benchmarks, customer proof, or community discussions
- Known risks, outdated claims, or conflicting descriptions
- Security or manipulation concerns

## Default Workflow

1. Define the entity and the exact facts that should be recognized.
2. Check official sources for clarity, consistency, dates, authorship, and structured evidence.
3. Check external sources for corroboration: reviews, customer stories, directories, analyst content, communities, benchmarks, and trusted publications.
4. Identify conflicts between official claims, third-party descriptions, user discussions, and AI-generated answers.
5. Separate credibility gaps from positioning gaps; credibility is about proof and source consistency, not new messaging.
6. Flag manipulation or safety risks such as hidden prompts, recommendation poisoning, unsupported claims, or unverifiable comparisons.
7. Prioritize source fixes by impact on discovery, citation, recommendation, and user trust.

## Branch Rules

- If third-party sources disagree with official positioning, hand off positioning decisions to GTM and record the visibility risk.
- If product facts are missing or unstable, hand off product decisions to Product and record what answer engines cannot verify.
- If prompt injection, memory poisoning, or hidden recommendation instructions appear, treat them as trust risks, not growth tactics.
- If the entity is new, separate "not yet known" from "known incorrectly."

## Anti-Patterns

- Trying to force citations through unsupported claims.
- Treating all mentions as positive visibility.
- Ignoring third-party descriptions because official copy is clear.
- Using manipulative prompts or hidden instructions as an AEO tactic.

## Acceptance Criteria

- Official and external sources support the target facts.
- Conflicts, missing proof, and outdated claims are visible.
- Recommendations distinguish source repair from GTM or Product decisions.
- Trust and manipulation risks are explicitly called out.

## Conflict Notes

Growth sources can imply aggressive optimization, while security sources warn that hidden manipulation damages trust. Treat credibility and verifiability as constraints on visibility work.

## Evidence Level

B
