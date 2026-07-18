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

## Search round A-003

Queries:

1. `site:dl.acm.org design rationale loss recovery controlled experiment architecture decision DOI`
2. `site:sciencedirect.com architecture decision recovery controlled experiment rationale DOI`
3. `site:link.springer.com requirements knowledge loss rework case study DOI`
4. `site:ieeexplore.ieee.org requirements rationale loss rework empirical DOI`

Purpose: locate empirical work on lost decision rationale, recovery of prior
decisions and consequences of missing requirements or intent.

Selected results registered from this round:

- E-010: https://doi.org/10.1016/j.scico.2011.11.008
- E-011: https://doi.org/10.1016/j.jss.2005.10.017

Selection note: E-010 was selected as the closest direct observation of
decision reconstruction. E-011 was selected for its explicit account of hidden
assumptions being rediscovered. Neither was classified as direct evidence of
all three C-002 components because neither measures consequential
organisational cost.

## Search round A-004

Queries:

1. `"The Lack of Shared Understanding of Non-Functional Requirements" DOI`
2. `"requirements" "rediscovery" software engineering empirical DOI`
3. `"intent loss" requirements engineering empirical study DOI`
4. `"rework" "shared understanding" requirements empirical case study DOI`

Purpose: distinguish requirements or intent rediscovery from ordinary
requirements change, communication failure and learning-cycle rework.

Selected result registered from this round:

- E-012: https://doi.org/10.1109/RE48521.2020.00021

Selection note: E-012 traces rework to gaps in shared understanding and also
reports that some rework is essential to rapid feedback. It does not establish
that unavailable intent had previously been retained and later lost.

## Search round A-005

Queries:

1. `decision rationale loss design rationale recovery empirical study software engineering DOI`
2. `requirements intent loss rediscovery rework empirical study software engineering DOI`
3. `unavailable prior reasoning rework rediscovery empirical study organization DOI`
4. `knowledge transfer internal stickiness nonuse empirical study Szulanski DOI`

Purpose: locate knowledge-transfer and non-use explanations that could account
for apparent retrieval or reconstruction problems without organisational
forgetting.

Selected result registered from this round:

- E-013: https://doi.org/10.1002/smj.4250171105

Selection note: E-013 was selected because it empirically distinguishes
transfer difficulty from simple motivation failure. Knowledge remains available
at a source, so the study is a competing mechanism rather than direct evidence
of memory loss or reconstruction.

## Search round A-006

Queries:

1. `site:pubsonline.informs.org redundant teams independent problem solving organizational performance empirical`
2. `site:sciencedirect.com "productive redundancy" organization knowledge empirical`
3. `site:academic.oup.com organizational redundancy independent verification decision making empirical`
4. `site:journals.sagepub.com rediscovery beneficial organizational learning empirical`

Purpose: actively seek contexts in which forgetting, parallel search,
independent interpretation or apparent duplication improves outcomes.

Selected results registered from this round:

- E-014: https://doi.org/10.1108/MD-03-2017-0200
- E-015: https://doi.org/10.1287/orsc.2015.0980

Selection note: E-014 provides a conditional beneficial-forgetting result.
E-015 demonstrates a coordination-versus-independent-exploration trade-off; it
does not study literal rediscovery, so it is retained only as a boundary on
classifying parallel work as waste.

## Round A-003 to A-006 limitations

- Searches used the same `web.run` / `search_query` interface and invocation
  constraints recorded above. Each listed round was one four-query invocation
  with `response_length: long`, no recency parameter and no explicit locale.
- The full ranked result sets were not exposed or captured. The query strings,
  selected durable identifiers and selection reasons are documented, but the
  result sets are not reproducible.
- Publisher records, abstracts and openly available papers support registration
  and triage only. All six new records require full-text appraisal and
  independent Evidence Review before any direction or claim assessment.
- No selected source directly measures prior organisational availability,
  later retrieval or application failure, and consequential reconstruction
  work in one design.
