# Lead.AI Labs Fraud Benchmark

Reproducible tabular evaluation and controlled model/benchmark publishing.

[Source repository](https://github.com/Arungharami/lead-ai-labs-hf-upgrade) · [Portfolio index](../README.md)

## Current foundation

Controlled synthetic reference benchmark; existing Gradio demonstration is rule based.

This roadmap was prepared from the repository README on October 4, 2026. It records proposed work, not completed experiments, production certification or a fresh test run. Resolve status disagreements against the project's authoritative artifacts before updating public claims.

## Materials to review

- [BENCHMARKS.md](https://github.com/Arungharami/lead-ai-labs-hf-upgrade/blob/HEAD/BENCHMARKS.md)
- [src/lead_ai_bench/](https://github.com/Arungharami/lead-ai-labs-hf-upgrade/tree/HEAD/src/lead_ai_bench/)
- [models/fraud-detection-xai/](https://github.com/Arungharami/lead-ai-labs-hf-upgrade/tree/HEAD/models/fraud-detection-xai/)
- [KAGGLE_BENCHMARK_DEPLOYMENT.md](https://github.com/Arungharami/lead-ai-labs-hf-upgrade/blob/HEAD/KAGGLE_BENCHMARK_DEPLOYMENT.md)

## Work packages

### 1. Audit dataset and bundle contracts

**Priority:** P0 · **State:** Proposed; completion evidence required

Validate binary targets, duplicate leakage, feature order, pinned runtime and checksums.

**Acceptance criteria:** Contract tests reject malformed inputs and bundle verification proves exact model/schema/runtime consistency.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 2. Add representative authorized data

**Priority:** P1 · **State:** Proposed; completion evidence required

Depends on compatible dataset terms and an adapter preserving untouched test data.

**Acceptance criteria:** Provenance, leakage audit, split manifest and real-data evaluation are recorded separately from synthetic results.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 3. Serve the verified trained model

**Priority:** P2 · **State:** Proposed; completion evidence required

Depends on accepted bundle. Replace or supplement the rule-based demo with explicit model loading.

**Acceptance criteria:** The app verifies bundle integrity, applies trained preprocessing and labels model versus demonstration outputs accurately.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

## Board handoff

Create or reuse repository issues for these packages after checking for existing equivalent work. Add those issues to the matching board, set the real status, and attach the source materials above. Do not create duplicate boards merely to increase project count.
