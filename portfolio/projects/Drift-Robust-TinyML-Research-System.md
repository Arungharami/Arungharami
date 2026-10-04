# Drift-Robust TinyML

Electronic-nose learning under chronological sensor drift.

[Source repository](https://github.com/Arungharami/Drift-Robust-TinyML-Research-System) · [Portfolio index](../README.md)

## Current foundation

Research pipeline; physical MCU measurements remain unavailable.

This roadmap was prepared from the repository README on October 4, 2026. It records proposed work, not completed experiments, production certification or a fresh test run. Resolve status disagreements against the project's authoritative artifacts before updating public claims.

## Materials to review

- [configs/](https://github.com/Arungharami/Drift-Robust-TinyML-Research-System/tree/HEAD/configs/)
- [results/registry/](https://github.com/Arungharami/Drift-Robust-TinyML-Research-System/tree/HEAD/results/registry/)
- [paper/claim_evidence_matrix.csv](https://github.com/Arungharami/Drift-Robust-TinyML-Research-System/blob/HEAD/paper/claim_evidence_matrix.csv)
- [docs/REPRODUCIBILITY.md](https://github.com/Arungharami/Drift-Robust-TinyML-Research-System/blob/HEAD/docs/REPRODUCIBILITY.md)

## Work packages

### 1. Reconcile stage evidence

**Priority:** P0 · **State:** Proposed; completion evidence required

Compare pipeline stage registry, result artifacts, claim matrix, README and portal; record any disagreements before editing claims.

**Acceptance criteria:** A stage-by-stage ledger identifies executed, failed and blocked work; every completed stage links to an artifact.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 2. Validate embedded export

**Priority:** P1 · **State:** Proposed; completion evidence required

Depends on the reconciled ledger. Use the frozen protocol and numerical equivalence gates before physical deployment.

**Acceptance criteria:** Export artifact, exact toolchain and equivalence report are recorded; failed checks remain visible.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 3. Measure real hardware

**Priority:** P1 · **State:** Proposed; completion evidence required

Depends on accepted export and access to nRF52840, probe and power measurement equipment.

**Acceptance criteria:** Flash, SRAM, latency and energy come from physical measurements with reproducible firmware and instrument settings.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

## Board handoff

Create or reuse repository issues for these packages after checking for existing equivalent work. Add those issues to the matching board, set the real status, and attach the source materials above. Do not create duplicate boards merely to increase project count.
