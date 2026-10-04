# FleetDesk

Single-owner rental operations from two cars to a larger fleet.

[Source repository](https://github.com/Arungharami/FleetDesk) · [Portfolio index](../README.md)

## Current foundation

Operational pilot with authenticated SQLite server and separate browser-only static demo.

This roadmap was prepared from the repository README on October 4, 2026. It records proposed work, not completed experiments, production certification or a fresh test run. Resolve status disagreements against the project's authoritative artifacts before updating public claims.

## Materials to review

- [docs/DEPLOYMENT.md](https://github.com/Arungharami/FleetDesk/blob/HEAD/docs/DEPLOYMENT.md)
- [docs/ROADMAP.md](https://github.com/Arungharami/FleetDesk/blob/HEAD/docs/ROADMAP.md)
- [README.md](https://github.com/Arungharami/FleetDesk/blob/HEAD/README.md)

## Work packages

### 1. Verify persistent owner deployment

**Priority:** P0 · **State:** Proposed; completion evidence required

Use persistent hosting for the Node server; configure owner authentication and HTTPS through secret settings.

**Acceptance criteria:** Records survive restart; unauthenticated requests fail; backup and restore are demonstrated without real customer data.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 2. Test rental settlement edge cases

**Priority:** P1 · **State:** Proposed; completion evidence required

Depends on accepted persistence. Exercise overlap, checkout, extensions, mileage, deposits and refund records.

**Acceptance criteria:** End-to-end cases preserve immutable payment history and document unresolved correction/overdue-charge behavior.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 3. Prepare controlled owner pilot

**Priority:** P2 · **State:** Proposed; completion evidence required

Depends on accepted flow and owner-approved business configuration.

**Acceptance criteria:** Fictional pilot covers rental lifecycle, maintenance, cash report and recovery; limitations and external agreement/payment responsibilities are clear.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

## Board handoff

Create or reuse repository issues for these packages after checking for existing equivalent work. Add those issues to the matching board, set the real status, and attach the source materials above. Do not create duplicate boards merely to increase project count.
