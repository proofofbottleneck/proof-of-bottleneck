# Public Disclosure Boundary

This document defines the public disclosure boundary for Proof of Bottleneck™ / PoB™ research.

The objective is to make research claims, evidence and validation limits inspectable without publishing implementation-sensitive or patent-sensitive mechanisms.

## What this repository may disclose

Public material may include:

- Research objectives
- High-level problem formulations
- Threat-model principles
- Falsification methodology
- Experimental setup at a high level
- Selected experimental outcomes
- Statistical summaries
- Validation limits
- Research maturity
- Public patent status
- Links between research questions and evidence

## What this repository intentionally withholds

Unless explicitly released, public material does not disclose:

- Admission and enforcement internals
- Certificate construction mechanisms
- Critical state-transition logic
- Operational thresholds
- Protected causal predicates
- Bypass-sensitive parameters
- Private test harness internals
- Complete implementation architecture
- Patent-sensitive claim construction
- Source code sufficient to reproduce protected mechanisms

## Why this boundary exists

Public evidence and complete implementation disclosure are not the same requirement.

A research claim can expose:

- what was tested
- what was observed
- what failed
- what survived
- what remains unverified

without exposing every mechanism required to reproduce the protected architecture.

The repository therefore separates **evidence transparency** from **implementation disclosure**.

## Intellectual-property status

Some research described by Proof of Bottleneck may be associated with filed or emerging intellectual-property work.

**NO-EXEC™ has a French patent application filed.**

Other research areas should not be interpreted as patented, patentable or novel unless explicitly stated.

No publication in this repository should be treated as a complete patent specification or as evidence of worldwide novelty.

## Security disclosure

Implementation details that could materially increase bypass, replication or attack capability may remain private.

This is not intended to conceal negative experimental results.

Negative results, failed hypotheses and validation limitations may be disclosed when they do not compromise protected implementation details.

## Validation language

Unless explicitly stated otherwise:

- internal testing is not independent validation
- prototype evidence is not production certification
- successful tested configurations do not imply universal security
- absence of an observed bypass is not proof that no bypass exists
- additional independent replication remains desirable

## Public documents

- [README.md](README.md)
- [RESEARCH.md](RESEARCH.md)
- [EVIDENCE.md](EVIDENCE.md)

---

**Expose the evidence. Protect the mechanism.**
