# OME project state

Last reviewed: 2026-07-18

This page is the orientation point for the public Organisational Memory
Engineering project. Read it first when joining or resuming the work.

It is a concise, source-linked view of current state—not a substitute for the
research records, Git history or pull-request decisions from which that state is
derived.

## Scope and authority

This file covers the public OME research and specification project only.
Product architecture, commercial strategy, customer information, security,
implementation roadmaps and private delivery work belong in the private company
repository, which should maintain its own project-state record.

When records disagree, use this precedence:

1. merged repository content and Git history;
2. accepted decisions and reviewed research records;
3. this project-state summary;
4. project-chat discussion;
5. human or AI memory.

Unmerged pull requests are proposals, not current repository policy.

## Current position

- **Phase:** Phase 1 — demonstrate the problem and test the integration gap.
- **Phase 0:** complete; the adjacent-disciplines review established the first
  reproducible research checkpoint.
- **Public canon:** none accepted.
- **RFC-0000:** not drafted. Its intended subject is *The Problem OME
  Addresses*, but the problem must first be supported by evidence.
- **Current framing:** OME is an engineering synthesis and research programme,
  not a proven new discipline.
- **Default quality rule:** no concept enters canon until its relationship to
  adjacent disciplines and its material evidence are reviewable.

## Complete

- Published the initial public research milestone on `main` at commit
  [`1f8febb`](https://github.com/OME-Foundation/ome-specification/commit/1f8febb97e1b2d404818edc7dfb0fb794e4429f1).
- Reviewed ten adjacent disciplines and separated source findings from OME
  interpretation.
- Classified founding concepts as Established, Synthesis, Hypothesis,
  Principle, Novel proposal or Open question.
- Retained no unsupported claim of novelty and deferred premature scalar
  metrics.
- Established the public discipline/private product boundary.

Primary sources:

- [Adjacent-disciplines review](research/adjacent-disciplines/README.md)
- [Synthesis and gap analysis](research/adjacent-disciplines/synthesis-and-gap-analysis.md)
- [Claim-classification governance](research/CLAIM_CLASSIFICATION.md)

## In review

- [Draft PR #1: Phase 1 research operating system](https://github.com/OME-Foundation/ome-specification/pull/1)
  proposes stable claim, evidence and research identifiers; evidence and
  counter-evidence rules; confidence and decision rules; templates; and the
  initial Phase 1 backlog.

PR #1 does not become part of project policy until it is reviewed and merged.

## In progress

No research investigation is currently in progress. Review of PR #1 is the
active work.

## Blocked or waiting

- Empirical Phase 1 research is waiting for review of the operating system so
  that evidence is recorded consistently from the start.
- The minimal integrated intervention and its comparative study design depend
  on first demonstrating a material, bounded problem and coverage gap.
- Canon drafting remains blocked by the evidence threshold, deliberately.

## Current research questions

1. When and with what consequences do organisations reconstruct reasoning that
   was previously available but cannot be retrieved or applied?
2. Do existing organisational-memory, knowledge-management, traceability,
   decision-rationale and provenance practices leave a material cross-lifecycle
   integration gap?
3. Is the perceived gap actually a failure of adoption, incentives or practice
   rather than a missing engineering integration?
4. If a bounded gap exists, what is the smallest intervention that addresses it
   without recreating established methods or imposing excessive capture cost?
5. Which observable outcomes could test that intervention without collapsing
   distinct properties into a premature index?

## Decisions changed during the latest milestone

- **Repository contents:** historical founding drafts were removed from public
  Git history; the repository contains what survived review, not everything
  considered.
- **Novelty:** integration is the candidate contribution; constituent concepts
  are inherited unless evidence demonstrates otherwise.
- **Terminology:** “Translation Loss” is not committed terminology; the
  phenomenon remains under investigation. “Decision Lineage” is formally
  treated as decision provenance and traceability. “Memory Debt” is discarded
  for now.
- **Measurement:** Knowledge Half-Life and a scalar Organisational Memory Index
  are not defensible current metrics. A multidimensional diagnostic profile is
  a possible future research direction.
- **Canon language:** proposed “laws” are principles or propositions unless
  evidence warrants stronger language.
- **Workflow:** substantive governance, evidence rules and eventual canon
  changes use pull-request review by default.

## Next decisions

1. Review PR #1 for bias, missing counter-evidence safeguards, usable record
   structure and appropriate decision thresholds.
2. Approve, revise or reject the proposed Phase 1 research operating system.
3. If approved, begin the first two investigations in parallel only where their
   scopes and evidence sources remain independent:
   - characterise consequential organisational reconstruction;
   - test the claimed cross-lifecycle coverage gap.
4. Update this file when those decisions change the merged state.

## Update discipline

Update `PROJECT_STATE.md` when a merged decision changes the phase, active work,
blockers, research questions or next decisions. Do not duplicate detailed
backlogs, evidence assessments or decision histories here; link to their
authoritative records.

Every update should:

- state its review date;
- distinguish merged state from proposals under review;
- identify the source commit, record or pull request;
- remove stale status rather than accumulating a sprint diary; and
- preserve the public/private boundary.

Automatic generation may be introduced only after the authoritative record
types are stable. Until then, this page is deliberately reviewed by a human as
part of each material project-state change.
