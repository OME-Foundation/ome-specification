# Research programme roles

Status: research governance; not an organisation chart or OME canon.

Roles define accountabilities and review boundaries. They do not assume a
particular team size or that a role is always filled by a human. A person or AI
agent may perform more than one role, but material overlaps must be declared and
cannot erase accountable review.

## Research Lead

Owns the question, protocol, execution record and delivery of a bounded research
item.

Accountable for:

- defining scope, exclusions, alternatives and learning criteria;
- registering protocol changes and negative findings;
- ensuring evidence and research records remain current; and
- separating results from interpretation.

The Research Lead cannot be the sole reviewer of evidence they selected or the
sole approver of the resulting claim decision.

## Evidence Reviewer

Critically assesses evidence provenance, relevance, method, limitations,
direction and lifecycle independently of the desired programme outcome.

Accountable for:

- challenging inclusion, exclusion and source-quality judgements;
- checking counter-evidence and missing-evidence risks;
- detecting shared datasets or non-independent sources; and
- triggering claim reassessment when evidence changes status.

## Architecture Reviewer

Tests whether research constructs, relationships and proposed integrations are
coherent with established disciplines and the public architecture.

Accountable for:

- detecting renamed or duplicated concepts;
- testing boundaries and downstream dependencies;
- identifying architecture consequences and failure modes; and
- preventing product implementation choices from becoming public theory.

Architecture review does not override empirical evidence.

## Canon Editor

Translates sufficiently mature, approved research into precise and coherent
candidate canon without strengthening its claims.

Accountable for:

- preserving classifications, scope, uncertainty and citations;
- maintaining terminology and cross-document consistency;
- separating normative principles from empirical findings; and
- refusing canon work that has not passed admission rules.

The Canon Editor does not decide that research is true by publishing it.

## Implementation Lead

Designs and operates reference implementations or experiments that can test
research claims. Product-specific work remains in the private repository.

Accountable for:

- mapping implementation choices to the claims they test;
- preserving operational observations and unintended effects;
- avoiding metrics designed only to confirm success; and
- keeping customer, security, product and commercial information private.

The Implementation Lead produces observations; they do not unilaterally judge
their evidential direction or canon significance.

## Accountable Approver

Makes the final approval and merge decision for material public changes after
review roles have reported.

Accountable for:

- confirming that required review occurred;
- resolving or explicitly accepting remaining objections;
- protecting public/private and research/canon boundaries; and
- recording deviations from governance.

Approval cannot turn weak evidence into strong evidence. If the Accountable
Approver rejects a research recommendation, the disagreement and reasoning are
recorded rather than rewriting the evidence assessment.

## Minimum separation for material claim decisions

A material claim decision requires, at minimum:

1. a named Research Lead;
2. an Evidence Reviewer who did not solely originate the evidence assessment;
3. Architecture Review when terminology, integration or public structure is
   affected; and
4. an Accountable Approver for merge.

When team size prevents full separation, disclose the overlap and obtain a
subsequent independent review before the claim enters canon or guides a public
standard.
