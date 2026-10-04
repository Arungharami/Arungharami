# Lead.AI Product Platform

Lead capture and business automation across web and mobile.

[Source repository](https://github.com/Arungharami/Lead-AI-product) · [Portfolio index](../README.md)

## Current foundation

Multi-platform MVP; payments, messaging and other production features remain incomplete.

This roadmap was prepared from the repository README on October 4, 2026. It records proposed work, not completed experiments, production certification or a fresh test run. Resolve status disagreements against the project's authoritative artifacts before updating public claims.

## Materials to review

- [backend/](https://github.com/Arungharami/Lead-AI-product/tree/HEAD/backend/)
- [frontend/PRODUCTION_SANITY.md](https://github.com/Arungharami/Lead-AI-product/blob/HEAD/frontend/PRODUCTION_SANITY.md)
- [DEPLOYMENT.md](https://github.com/Arungharami/Lead-AI-product/blob/HEAD/DEPLOYMENT.md)
- [FINAL_RELEASE_CHECKLIST.md](https://github.com/Arungharami/Lead-AI-product/blob/HEAD/FINAL_RELEASE_CHECKLIST.md)

## Work packages

### 1. Verify one complete lead flow

**Priority:** P0 · **State:** Proposed; completion evidence required

Choose and document the canonical backend entry point; exercise chat, authenticated save and lead retrieval.

**Acceptance criteria:** An end-to-end test proves correct user ownership and useful error behavior from client through storage.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 2. Harden deployment boundaries

**Priority:** P1 · **State:** Proposed; completion evidence required

Depends on canonical API; inspect authorization, CORS, secret handling, Firestore access and abuse controls.

**Acceptance criteria:** Unauthorized access and abusive requests fail in tests; deployment configuration and recovery steps are documented.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 3. Deliver one approved integration

**Priority:** P2 · **State:** Proposed; completion evidence required

Depends on validated MVP. Select one business integration and define its success/failure contract.

**Acceptance criteria:** Sandbox workflow, duplicate-event handling, retry behavior and setup instructions pass before production activation.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

## Board handoff

Create or reuse repository issues for these packages after checking for existing equivalent work. Add those issues to the matching board, set the real status, and attach the source materials above. Do not create duplicate boards merely to increase project count.
