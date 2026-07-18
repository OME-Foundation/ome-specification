# Architecture and governance decisions

Last reviewed: 2026-07-18

This is a living orientation index, not a replacement for Architecture Decision
Records (ADRs) or the records linked below. It summarises current public OME
decisions and proposals so a new contributor can find their authoritative
rationale quickly.

An entry marked `Proposed` is not a decision. It reflects an open pull request
and becomes accepted only if that change is reviewed and merged.

## Decision index

| Area | Current decision or proposal | Status | Source record |
| --- | --- | --- | --- |
| Project authority | Merged authoritative records and Git history are canonical; open PRs contain proposals; project state is derived; chat and memory are non-authoritative. | Accepted | [`PROJECT_STATE.md`](PROJECT_STATE.md) |
| Contributor continuity | Humans and AI agents are replaceable and should recover project context from repository records. | Accepted | [`PROJECT_STATE.md`](PROJECT_STATE.md) |
| Public/private boundary | Public Git contains OME research and future specifications; commercial product and implementation work remain private. | Accepted | [`README.md`](README.md) at milestone [`1f8febb`](https://github.com/OME-Foundation/ome-specification/commit/1f8febb97e1b2d404818edc7dfb0fb794e4429f1) |
| Canon admission | A concept cannot enter OME canon until its relationship to adjacent disciplines is documented. | Accepted | [`research/CLAIM_CLASSIFICATION.md`](research/CLAIM_CLASSIFICATION.md) |
| Claim classification | Claims use six classes: Established, Synthesis, Hypothesis, Principle, Novel proposal and Open question. | Accepted | [`research/CLAIM_CLASSIFICATION.md`](research/CLAIM_CLASSIFICATION.md) |
| OME positioning | OME is currently an engineering synthesis and research programme, not a proven new discipline. | Accepted | [`README.md`](README.md) and [synthesis](research/adjacent-disciplines/synthesis-and-gap-analysis.md) |
| Phase 1 research records | Claims, evidence and research items use stable related identifiers and explicit decision rules. | Accepted | [Research operating system](research/operating-system/README.md) |
| Canon development | No RFC or OME specification is accepted; problem evidence precedes canon drafting. | Accepted | [`README.md`](README.md) and research basis in the [synthesis](research/adjacent-disciplines/synthesis-and-gap-analysis.md) |

## ADR status

No public ADR series has been established yet. The absence of an ADR does not
authorise this index to invent an identifier or reconstruct rationale from
memory. When an ADR is created, its stable identifier replaces the interim
source link in the table; the underlying decision history remains in Git.

## Maintenance rules

- Add only decisions that materially affect research, governance, public
  architecture or contributor behaviour.
- Distinguish `Proposed`, `Accepted`, `Superseded` and `Rejected` explicitly.
- Link the authoritative ADR, research record, merged pull request or commit.
- Do not copy detailed rationale out of the source record.
- Update superseded decisions rather than silently deleting their history.
- Keep private product architecture and commercial decisions in the private
  repository's decision index.
- Update this index in the same pull request that changes a listed decision.
