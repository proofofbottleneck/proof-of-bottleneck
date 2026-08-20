# Research Program

Proof of Bottleneck™ / PoB™ is an independent research initiative focused on verifiable AI & systems safety.

The objective is to study architectures in which critical safety properties can be tested, falsified and independently verified rather than accepted as trust-based assertions.

## Current research areas

### Verifiable non-execution

Can a system produce evidence that a forbidden execution path was not entered — rather than merely recording a denial decision?

Flagship work: **NO-EXEC™**

**French patent application filed.**

### Causal security

Research into security properties defined by causal structure rather than by permissions, logs or post-event detection alone.

### Compositional safety

Study of whether individually permitted actions can combine into a globally forbidden or unsafe state.

### Irreversible-action control

Architectures intended to constrain, delay or certify actions whose consequences cannot easily be reversed.

### Multi-agent systems

Research into safety properties that must survive interaction between multiple autonomous or semi-autonomous agents.

### Formal safety invariants

Exploration of compact properties that can remain testable across changing implementations, environments and execution paths.

## Experimental methodology

Research is conducted through an iterative falsification process:

1. Define a narrow technical claim
2. Construct a falsifiable baseline
3. Build an adversarial test
4. Measure observable outcomes
5. Attempt to break the hypothesis
6. Preserve only claims supported by surviving evidence
7. Seek replication on additional environments

Experimental work has progressed from mobile / Termux prototypes to bare-metal infrastructure.

## Termux23

Experimental work is conducted with **Termux23**, a small independent technical team focused on prototyping, adversarial testing and falsification.

> Break the hypothesis before asking anyone else to trust it.

## Research status

Work described in this repository includes research hypotheses, prototypes and experimental results at different maturity levels.

Unless explicitly stated otherwise:

- results should not be interpreted as universal proofs
- prototype success does not imply production readiness
- internal validation is not equivalent to independent validation
- novelty should not be assumed without prior-art analysis
- implementation-sensitive details may remain intentionally undisclosed

## Public research boundary

This repository documents research questions, selected evidence, methodology and validation limits.

It is not intended to disclose complete implementations of protected or potentially patent-sensitive mechanisms.

See also:

- [EVIDENCE.md](EVIDENCE.md)
- [README.md](README.md)

---

**Research first. Claims second. Evidence before trust.**
