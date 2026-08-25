# Decisions

This file records durable project decisions. Amend existing entries instead of silently changing conventions.

## 2026-08-25 — Repository scope

bg-prolate-spheroid is the canonical repository for the prolate-spheroid branch of the basepoint-geometry program.

The repository must not mix oblate, triaxial, frustum, polyhedral, or general-theory calculations into the prolate certification path.

## 2026-08-25 — Public terminology

Public-facing text uses neutral mathematical terms:

- radial–normal angle;
- stationary base point;
- stationary orbit;
- cone-volume measure.

Project-specific interpretive terminology is not required for the mathematical statements.

## 2026-08-25 — Evidence separation

Exact derivations, interval certification, high-precision computation, exploratory diagnostics, and non-binding material are separate evidence classes.

A stronger label may replace a weaker one only when the new derivation and reproduction instructions are committed in the same revision.

## 2026-08-25 — Numerical records

A bare decimal is not a result. Every reported number must include:

- the quantity and normalization;
- the parameter domain;
- the derivation class;
- precision and tolerances;
- software and version where material;
- a reproducible source or command;
- an independent verification note when promoted toward certification.

## 2026-08-25 — Manuscript precedence

The repository is supporting material. The identified submitted or published manuscript governs whenever wording, notation, or claims conflict. The governing manuscript version must be recorded in STATUS.md before a release is tagged.

## 2026-08-25 — Release gate

Before any research release or tag:

1. freeze the relevant source files;
2. run the documented reproduction path;
3. perform an independent verification;
4. confirm that manuscript, tables, and code use the same normalization;
5. record hashes and the verification outcome.
