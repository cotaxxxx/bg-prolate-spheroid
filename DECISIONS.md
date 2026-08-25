# Decisions

This file records durable case-specific project decisions. The normative
cross-repository rules are in [RESEARCH_RULES.md](RESEARCH_RULES.md).

## 2026-08-25 — Repository scope

`bg-prolate-spheroid` is the canonical repository for the prolate-spheroid
branch of the basepoint-geometry program.

Oblate, triaxial, frustum, polyhedral, and general-theory calculations do not
enter the prolate certification path.

## 2026-08-25 — Rules vocabulary

Evidence class and numerical derivation class remain separate. This repository
uses exactly the vocabulary of `RESEARCH_RULES.md`; it does not define a local
“verification class.”

## 2026-08-25 — Governance pin

The governing rules and workflow baseline are
`cotaxxxx/basepoint-geometry@d0a77680997c768d3be5194936814bed74833fe2`.
See [GOVERNANCE_PIN.md](GOVERNANCE_PIN.md).

A future local workflow must be pinned by exact path and SHA before it enters
the proof path.

## 2026-08-25 — Public terminology

Public-facing text uses neutral mathematical terms: radial–normal angle,
stationary base point, stationary orbit, and cone-volume measure.

## 2026-08-25 — Numerical records

A bare decimal is not a result. Every number must carry its numerical
derivation class and reproducibility record as required by Research Rule 2.

## 2026-08-25 — Normalization

The canonical functional uses the probability measure

\[
d\mu_{K,p}
=
\frac{(x-p)\cdot\nu}{3\,\operatorname{Vol}(K)}\,dA.
\]

The reduced spheroidal coefficient \(1/2\) is a consequence of this
normalization after azimuthal integration; it is not an unnormalized
alternative.

## 2026-08-25 — Author identity

Public attribution uses the real name `古田勝士`. The repository does not use
`DAYBREAK` as an alternative author identity.

## 2026-08-25 — DOI before migration

The fixed long-spheroid result set receives its DOI before content migration
begins. Migration must not change the deposited DOI object and must preserve
source hashes and provenance.

## 2026-08-25 — Release gate

Before any research release or tag:

1. freeze the relevant source files;
2. run the documented reproduction path;
3. perform an independent verification;
4. confirm that manuscript, tables, and code use the same normalization;
5. record rules, workflow, source, and artifact hashes;
6. record the DOI and governing manuscript version.
