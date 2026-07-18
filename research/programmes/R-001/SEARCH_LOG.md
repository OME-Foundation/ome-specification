# R-001 search log

Status: Stage A exploratory search; not the frozen Stage B search.

Search date: 2026-07-18

Interface: OpenAI web-search tool exposed to the Codex desktop research agent as
`web.run` using its `search_query` operation. Each round submitted four queries
in one invocation with `response_length: long`. No recency parameter or explicit
locale was supplied. Domain restrictions were used only where written into a
query with `site:`. The underlying search provider, ranking configuration and
complete result set were not exposed.

These records provide documented exploratory queries and source-selection
provenance. They do not provide exact or reproducible result-set provenance and
do not constitute a systematic or exhaustive database search.

## Search round A-001

Queries:

1. `organizational forgetting empirical study beneficial forgetting unlearning primary paper DOI`
2. `employee turnover knowledge loss organizational performance empirical study DOI`
3. `organizational memory failure knowledge retrieval reconstruction rework empirical study DOI`
4. `transactive memory system expertise retrieval team performance empirical study DOI`

Purpose: seek both harmful-loss mechanisms and alternatives involving turnover,
expertise location, unlearning and beneficial forgetting.

Candidate families identified:

- turnover-induced knowledge loss;
- transactive memory systems;
- empirical forgetting/unlearning research;
- turnover-performance meta-analysis; and
- knowledge-management implementation barriers.

Selected results registered from this round:

- E-007: https://doi.org/10.1111/joms.12096
- E-009: https://doi.org/10.1287/mnsc.1040.0257

## Search round A-002

Queries:

1. `site:pubsonline.informs.org organizational forgetting de Holan Phillips Lawrence DOI`
2. `site:journals.sagepub.com organizational forgetting beneficial empirical DOI`
3. `site:onlinelibrary.wiley.com organizational unlearning empirical study DOI Tsang Zahra`
4. `site:academic.oup.com organizational forgetting productivity employee turnover learning curve empirical`

Purpose: locate primary and publisher records for central, beneficial and
disconfirming sources.

Candidate sources registered from these rounds:

- E-004: exploratory multiple-case study of organisational forgetting;
- E-005: critical argument for beneficial organisational forgetting;
- E-006: inside-firm empirical challenge to large forgetting estimates;
- E-007: turnover-related knowledge loss across service/manufacturing contexts;
- E-008: structural buffering of turnover effects in federal IT projects; and
- E-009: longitudinal transactive-memory study in knowledge-worker teams.

Selected results registered from this round:

- E-004: https://doi.org/10.1287/mnsc.1040.0273
- E-005: https://doi.org/10.1177/1056492611408508
- E-006: https://doi.org/10.1177/001979391206500104
- E-008: https://doi.org/10.1093/jopart/muaf019

## Limitations and next searches

- Search-engine retrieval is not reproducible enough for Stage B and may omit
  paywalled, non-indexed, non-English and null-result studies.
- The full ranked result sets were not captured; only selected durable source
  identifiers are recorded.
- Search snippets and abstracts support triage, not full methodological review.
- “Reconstruction” produced few direct organisational results and may not be the
  established term.
- Decision-rationale loss, requirements rediscovery, knowledge-transfer
  stickiness and beneficial rediscovery require dedicated searches.
- Each registered record remains `Registered`; full-text appraisal and
  independent Evidence Review are pending.
