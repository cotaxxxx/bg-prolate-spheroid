# Research Status

Updated: 2026-08-25

## Global status

`NOT_BINDING / DIAGNOSTIC_ONLY`

This repository currently contains no certified theorem, certified numerical
value, approved production kernel, or Actions-produced clean-room certificate.

## Project

**Shape family:** prolate spheroids  
**Functional:** cone-volume-weighted squared radial–normal angle  
**Primary question:** how the stationary base-point set changes as the aspect ratio varies

The prolate case is treated through rotational symmetry and reduction to the
long axis. A final record must distinguish existence, orbit type, axial and
transverse second variation, bifurcation thresholds, and claim scope.

## Classification contract

Evidence classes and numerical derivation classes are separate and are defined
normatively in [RESEARCH_RULES.md](RESEARCH_RULES.md).

Evidence classes: `DIAGNOSTIC_ONLY`, `NOT_BINDING`, `PROTOTYPE`,
`NOT_AUDITED`, `AUDITED_SOURCE`, and `CERTIFIED`.

Numerical derivation classes: `EXACT`, `CERTIFIED_ENCLOSURE`,
`HIGH_PRECISION`, `FLOAT`, and `EXTRAPOLATED`.

No combined “verification class” is used.

## Normalization

The functional uses the probability measure

\[
d\mu_{K,p}
=
\frac{(x-p)\cdot\nu}{3\,\operatorname{Vol}(K)}\,dA.
\]

For a rotational spheroid with polar semiaxis \(\lambda\),

\[
\int_{\partial K}(x-p)\cdot\nu\,dA
=
3\operatorname{Vol}(K)
=
4\pi\lambda.
\]

After the azimuthal integration, the normalized axial energy therefore has the
factor \(1/2\). This is the same normalization used by the oblate axial formula.

## Governance

Rules and workflow baseline are pinned in [GOVERNANCE_PIN.md](GOVERNANCE_PIN.md).

## Current repository state

Only the repository framework and research-governance documents are present.
No long-spheroid numerical thresholds or certification claims have been
migrated.

## Publication order

1. Freeze and identify the long-spheroid result set.
2. Deposit the fixed result set and obtain its DOI.
3. Record the DOI and governing manuscript version here.
4. Only then begin migration into this repository.
5. Preserve hashes and provenance during migration.
