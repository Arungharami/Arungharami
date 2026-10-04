# Customer Behavior Research — Part 2

Temporal stability, calibration, explanation stability and operational value.

[Source repository](https://github.com/Arungharami/Customer-Behavior-Prediction-in-Banking-and-Insurance-2) · [Portfolio index](../README.md)

## Current foundation

Protocol and preflight utilities exist; empirical manuscript results require authorized data and execution.

This roadmap was prepared from the repository README on October 4, 2026. It records proposed work, not completed experiments, production certification or a fresh test run. Resolve status disagreements against the project's authoritative artifacts before updating public claims.

## Materials to review

- [config/research.yaml](https://github.com/Arungharami/Customer-Behavior-Prediction-in-Banking-and-Insurance-2/blob/HEAD/config/research.yaml)
- [docs/PAPER_BLUEPRINT.md](https://github.com/Arungharami/Customer-Behavior-Prediction-in-Banking-and-Insurance-2/blob/HEAD/docs/PAPER_BLUEPRINT.md)
- [docs/FIGURE_TABLE_REGISTRY.md](https://github.com/Arungharami/Customer-Behavior-Prediction-in-Banking-and-Insurance-2/blob/HEAD/docs/FIGURE_TABLE_REGISTRY.md)
- [docs/WIJAR_SUBMISSION_GATE.md](https://github.com/Arungharami/Customer-Behavior-Prediction-in-Banking-and-Insurance-2/blob/HEAD/docs/WIJAR_SUBMISSION_GATE.md)

## Work packages

### 1. Complete dataset preflight

**Priority:** P0 · **State:** Proposed; completion evidence required

Record authorized benchmark files, terms, schemas and deployment-time feature availability.

**Acceptance criteria:** Preflight passes only on real authorized data; temporal assumptions and excluded leakage features are documented.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 2. Implement and execute empirical stages

**Priority:** P1 · **State:** Proposed; completion evidence required

Depends on accepted preflight and frozen splits; persist fitted preprocessing with each model.

**Acceptance criteria:** Baselines yield discrimination, calibration, stability, explanation and efficiency artifacts with provenance.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 3. Build submission evidence package

**Priority:** P2 · **State:** Proposed; completion evidence required

Depends on accepted empirical runs; generate figures and tables from those runs.

**Acceptance criteria:** Research gate passes; each manuscript value maps to an artifact and the blind manuscript has no identifying metadata.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

## Board handoff

Create or reuse repository issues for these packages after checking for existing equivalent work. Add those issues to the matching board, set the real status, and attach the source materials above. Do not create duplicate boards merely to increase project count.
