# Basepoint Geometry of the Prolate Spheroid

This repository records the prolate-spheroid branch of the basepoint-geometry research program.

The object of study is the cone-volume-weighted radial–normal angle functional

[
E_K(p)=int_{partial K}alpha_{K,p}(x)^2,dmu_{K,p}(x),
]

where

[
alpha_{K,p}(x)
=arccos!left(
rac{(x-p)cdot 
u(x)}{|x-p|}
ight),
qquad
dmu_{K,p}(x)
=rac{(x-p)cdot 
u(x)}{3,mathrm{Vol}(K)},dA(x).
]

Here (Ksubsetmathbb R^3) is a convex body, (pinoperatorname{int}K), and (
u) is the outer unit normal.

## Scope

This repository is restricted to prolate spheroids and their stationary base points. Its principal themes are:

- symmetry reduction to the long axis;
- stationary-orbit bifurcation as the aspect ratio varies;
- transverse stability of axial stationary points;
- reproducible numerical exploration;
- rigorous certification of the reported bifurcation picture.

The terminology used here is deliberately neutral: *radial–normal angle*, *stationary base point*, and *stationary orbit*.

## Research status

The research record is divided by evidential role:

- [STATUS.md](STATUS.md) — current results, open questions, and verification state;
- [DECISIONS.md](DECISIONS.md) — durable conventions and methodological decisions;
- future analytic or computational material should be placed in clearly named subdirectories and linked from STATUS.md.

No numerical value is authoritative merely because it appears in a script or exploratory output. Each reported quantity must state its derivation class, precision, and verification method.

## Repository policy

This repository is a research record, not a substitute for the submitted manuscript or its peer-reviewed version. If the repository and the manuscript differ, the manuscript version identified in STATUS.md governs.

Exploratory calculations must be marked **NOT_BINDING** until independently reproduced or rigorously certified.

## Author

Independent research by DAYBREAK, a graduate of the College of Law, Ritsumeikan University.
