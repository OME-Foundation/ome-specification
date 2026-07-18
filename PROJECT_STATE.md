# OME project state

Last reviewed: 2026-07-18

This is a reviewed, derived orientation view for the public Organisational
Memory Engineering project. It is not canonical and does not replace the
authoritative records linked below.

## Authority and scope

Use this precedence when recovering project context:

1. **Merged authoritative records and Git history** — canonical research,
   governance, decisions and specifications.
2. **Open pull requests** — proposed changes and unresolved review discussion.
3. **`PROJECT_STATE.md`** — a reviewed summary derived from those sources.
4. **Project chat** — working discussion and uncommitted ideas.
5. **Human or assistant memory** — non-authoritative behavioural and orientation
   hints only.

Humans and AI agents are deliberately replaceable. Nothing architectural or
governance-critical should live exclusively in memory.

This file covers public OME research and specification work. Private product,
customer, security, commercial and implementation state belongs in the private
company repository.

## Current phase and objective

- **Phase:** Phase 1 — problem and integration-gap validation.
- **Objective:** determine whether organisations experience a consequential
  problem that existing disciplines address only partially, and whether an
  integrated engineering approach could measurably improve it.
- **Current framing:** OME is an engineering synthesis and research programme,
  not a proven new discipline.
- **Canon:** none accepted; no RFC is open.

Authoritative sources:

- [Research operating system](research/operating-system/README.md)
- [Claim Register](research/operating-system/CLAIMS.md)
- [Evidence Register](research/operating-system/EVIDENCE.md)
- [Research Backlog](research/operating-system/BACKLOG.md)
- [Architecture and governance decision index](ARCHITECTURE_DECISIONS.md)

## Active work

`R-001` remains in Stage A. The approved
[C-002 construct assessment](research/programmes/R-001/C-002_CONSTRUCT_ASSESSMENT.md)
records disposition `Defer` at `Very low` confidence while retaining
classification `Hypothesis`. Nine Stage A evidence records have completed
independent review; E-006 through E-008 remain registered evidence gaps because
full-text appraisal is incomplete. Stage A remains incomplete, and the
assessment does not authorise Stage B.

`R-002`, testing the claimed cross-lifecycle coverage gap, remains ready but has
not started.

See the [Research Backlog](research/operating-system/BACKLOG.md) for scope,
methods, dependencies and completion evidence.

## Blockers

- `R-003`, the minimal integrated intervention, is blocked until `R-001` and
  `R-002` establish a material, bounded gap.
- `R-004`, comparative outcomes and study design, is blocked on a testable
  intervention from `R-003`.
- Canon drafting is blocked until the material problem claims satisfy the
  [confidence and decision rules](research/operating-system/DECISION_RULES.md).

## Key risks

- **Confirmation bias:** searching to justify OME rather than attempting to
  reject or narrow its claims.
- **Self-validation:** treating internal synthesis as independent evidence.
- **Premature canonisation:** allowing repeated terminology or workflow status
  to imply truth.
- **State drift:** permitting this summary to diverge from authoritative
  records.
- **Boundary leakage:** mixing public research with private company information.

## Next decisions

1. Preserve E-006 through E-008 as explicit gaps and reopen the C-002 assessment
   if later appraisal meets a recorded reopening condition.
2. Decide whether any further R-001 proposal should address the evidence gaps;
   do not design or begin Stage B without express reviewed authorisation.
3. Decide when to begin `R-002` without duplicating or biasing R-001.
4. Keep C-002 out of canon and dependent premises while its disposition remains
   `Defer` at `Very low` confidence.

## Update rule

Update this view when a merged change alters the phase, objective, active work,
blockers, key risks or next decisions. Link authoritative records instead of
copying their histories or detailed contents.

Every update requires explicit accountable review through a pull request. AI or
human contributors may prepare and review it; approval and merge retain human
accountability. Remove stale state rather than accumulating a sprint diary.
