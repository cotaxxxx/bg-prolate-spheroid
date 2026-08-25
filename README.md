# Basepoint Geometry of the Prolate Spheroid

This repository records the prolate-spheroid branch of the basepoint-geometry research program.

> **Repository status: `NOT_BINDING / DIAGNOSTIC_ONLY`**
>
> This repository currently contains no certified theorem, approved production
> kernel, or Actions-produced clean-room certificate.

The object of study is the cone-volume-weighted radial–normal angle functional

\[
E_K(p)=\int_{\partial K}\alpha_{K,p}(x)^2\,d\mu_{K,p}(x),
\]

where

\[
\alpha_{K,p}(x)
=\arccos\!\left(
\frac{(x-p)\cdot \nu(x)}{|x-p|}
\right),
\qquad
d\mu_{K,p}(x)
=\frac{(x-p)\cdot \nu(x)}{3\,\mathrm{Vol}(K)}\,dA(x).
\]

Here \(K\subset\mathbb R^3\) is a convex body, \(p\in\operatorname{int}K\), and
\(\nu\) is the outer unit normal.

## Normalization check

The measure above is a probability measure because

\[
\int_{\partial K}(x-p)\cdot\nu\,dA=3\,\mathrm{Vol}(K).
\]

For a rotational spheroid with polar semiaxis \(\lambda\), this denominator is
\(4\pi\lambda\). The azimuthal integration supplies \(2\pi\lambda\), leaving
the coefficient \(1/2\) in the reduced axial formula. Thus the prolate and
oblate repositories use the same normalized mean energy.

## Scope

This repository is restricted to prolate spheroids and their stationary base
points. Its principal themes are symmetry reduction to the long axis,
stationary-orbit bifurcation, transverse stability, reproducible computation,
and rigorous certification.

## Current state and publication order

No result migration has begun. The fixed long-spheroid result set must receive
its DOI before migration into this repository.

## Repository documents

- [Research rules](RESEARCH_RULES.md)
- [Governance pin](GOVERNANCE_PIN.md)
- [Research status](STATUS.md)
- [Case-specific decisions](DECISIONS.md)

## Author

古田勝士  
Independent researcher; graduate of the College of Law, Ritsumeikan University.
