# SitaRam

Source-grounded Ramayana study with multilingual reading and assistance.

[Source repository](https://github.com/Arungharami/SitaRam) · [Portfolio index](../README.md)

## Current foundation

Flutter application and corpus gates exist; corpus coverage remains incomplete.

This roadmap was prepared from the repository README on October 4, 2026. It records proposed work, not completed experiments, production certification or a fresh test run. Resolve status disagreements against the project's authoritative artifacts before updating public claims.

## Materials to review

- [assets/content/coverage_report.json](https://github.com/Arungharami/SitaRam/blob/HEAD/assets/content/coverage_report.json)
- [tools/validation/](https://github.com/Arungharami/SitaRam/tree/HEAD/tools/validation/)
- [huggingface_space/](https://github.com/Arungharami/SitaRam/tree/HEAD/huggingface_space/)
- [docs/PLAY_STORE_RELEASE_RUNBOOK.md](https://github.com/Arungharami/SitaRam/blob/HEAD/docs/PLAY_STORE_RELEASE_RUNBOOK.md)

## Work packages

### 1. Reconcile corpus coverage and provenance

**Priority:** P0 · **State:** Proposed; completion evidence required

Register editions and distinguish imported, verified, app-approved and retrieval-approved content.

**Acceptance criteria:** Coverage report matches records; each approval has authentic review evidence and registered source provenance.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 2. Validate relevant retrieval and feedback

**Priority:** P1 · **State:** Proposed; completion evidence required

Depends on approved evidence. Test irrelevant queries, language/Kanda restrictions, citations and persistence.

**Acceptance criteria:** Answers use only relevant approved excerpts; no-evidence behavior works; feedback is durably stored or explicitly described as unimplemented.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 3. Prepare internal testing release

**Priority:** P2 · **State:** Proposed; completion evidence required

Depends on content and backend gates; follow the release runbook.

**Acceptance criteria:** Flutter, backend and corpus checks pass; signed artifact checksum and internal testing evidence are recorded.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

## Board handoff

Create or reuse repository issues for these packages after checking for existing equivalent work. Add those issues to the matching board, set the real status, and attach the source materials above. Do not create duplicate boards merely to increase project count.
