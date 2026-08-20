# Public Experimental Evidence

This document records selected public experimental evidence associated with Proof of Bottleneck™ research.

It is intentionally disclosure-minimized.

## NO-EXEC™

NO-EXEC™ investigates whether a denied workload can be stopped before protected resource allocation while leaving independently auditable evidence that the forbidden execution path was not entered.

**French patent application filed.**

### Public experimental signals

Testing progressed from mobile / Termux environments to bare-metal infrastructure.

Selected results disclosed publicly:

- Bare-metal ADMIT / DENY heavy campaign: **PASS 5/5**
- Statistical result: **p = 0.0005**
- Measured energy separation: **≈ 5.66×**

These figures refer to specific experimental campaigns and tested configurations.

They should not be interpreted as proof of universal non-execution, immunity to all bypasses, production readiness or independent industrial validation.

## Evidence philosophy

The objective is not to produce favorable demonstrations.

The objective is to construct falsifiable tests capable of breaking the underlying hypothesis.

Public evidence is therefore presented with explicit boundaries between:

- what was measured
- what was inferred
- what remains unverified
- what remains intentionally undisclosed

## Publicly disclosed

- Research objective
- High-level threat-model assumptions
- High-level experimental outcomes
- Falsification posture
- Mobile-to-bare-metal progression
- Selected statistical and energy measurements

## Intentionally withheld

To preserve the implementation and intellectual-property boundary, this repository does not disclose:

- Admission and enforcement internals
- Certificate construction mechanisms
- Critical state transitions
- Operational thresholds
- Bypass-sensitive parameters
- Complete executable implementation

## Validation status

Current evidence is **prototype-level experimental evidence**.

Independent replication and evaluation on additional infrastructure remain desirable.

No result published here should be treated as a claim of universal security or impossibility.

---

**Evidence before trust.**
