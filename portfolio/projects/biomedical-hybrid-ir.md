# Biomedical Hybrid IR

Comparing lexical, dense, hybrid and reranked biomedical search.

[Source repository](https://github.com/Arungharami/biomedical-hybrid-ir) · [Portfolio index](../README.md)

## Current foundation

README reports six NFCorpus systems; broader research validation remains next work.

This roadmap was prepared from the repository README on October 4, 2026. It records proposed work, not completed experiments, production certification or a fresh test run. Resolve status disagreements against the project's authoritative artifacts before updating public claims.

## Materials to review

- [configs/](https://github.com/Arungharami/biomedical-hybrid-ir/tree/HEAD/configs/)
- [results/](https://github.com/Arungharami/biomedical-hybrid-ir/tree/HEAD/results/)
- [docs/dataset.md](https://github.com/Arungharami/biomedical-hybrid-ir/blob/HEAD/docs/dataset.md)
- [docs/models.md](https://github.com/Arungharami/biomedical-hybrid-ir/blob/HEAD/docs/models.md)
- [docs/reproducibility.md](https://github.com/Arungharami/biomedical-hybrid-ir/blob/HEAD/docs/reproducibility.md)

## Work packages

### 1. Audit evaluation completeness

**Priority:** P0 · **State:** Proposed; completion evidence required

Verify qrels denominator, omitted-query behavior and candidate-depth limitations.

**Acceptance criteria:** Regression checks include missing queries; Recall@100 and MAP limitations for reranking are explicit.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 2. Run validation-only tuning

**Priority:** P1 · **State:** Proposed; completion evidence required

Depends on audited metrics. Freeze a search budget for lexical parameters, fusion and reranking.

**Acceptance criteria:** Tuning uses validation judgments only; test results are generated once from selected configurations.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 3. Broaden benchmark evidence

**Priority:** P2 · **State:** Proposed; completion evidence required

Depends on frozen tuning policy. Add a documented biomedical benchmark and comparisons with uncertainty.

**Acceptance criteria:** Dataset terms, qrels, splits, per-query outputs, confidence intervals and multiple-comparison policy are recorded.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

## Board handoff

Create or reuse repository issues for these packages after checking for existing equivalent work. Add those issues to the matching board, set the real status, and attach the source materials above. Do not create duplicate boards merely to increase project count.
