# DailyOps

Mobile planning for classes, research and work.

[Source repository](https://github.com/Arungharami/dailyops-ai-agent) · [Portfolio index](../README.md)

## Current foundation

Browser-local calendar prototype with rule-based extraction; no cross-device calendar sync.

This roadmap was prepared from the repository README on October 4, 2026. It records proposed work, not completed experiments, production certification or a fresh test run. Resolve status disagreements against the project's authoritative artifacts before updating public claims.

## Materials to review

- [README.md](https://github.com/Arungharami/dailyops-ai-agent/blob/HEAD/README.md)

## Work packages

### 1. Make the public demo generic

**Priority:** P0 · **State:** Proposed; completion evidence required

Separate personal starter schedules from shareable example fixtures.

**Acceptance criteria:** Public demonstration uses fictional schedules and accurately describes local-only storage.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 2. Validate planning and timezone behavior

**Priority:** P1 · **State:** Proposed; completion evidence required

Depends on generic fixtures. Test overnight routines, timezone changes, overlaps and deletion.

**Acceptance criteria:** Expected dates and conflicts pass deterministic tests; preview lets users review extraction before saving.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 3. Design opt-in calendar synchronization

**Priority:** P2 · **State:** Proposed; completion evidence required

Depends on an authenticated integration design; define scopes, recurrence and duplicate handling.

**Acceptance criteria:** A reviewed design and sandbox tests cover consent, timezone, recurrence, idempotency and disconnect behavior before activation.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

## Board handoff

Create or reuse repository issues for these packages after checking for existing equivalent work. Add those issues to the matching board, set the real status, and attach the source materials above. Do not create duplicate boards merely to increase project count.
