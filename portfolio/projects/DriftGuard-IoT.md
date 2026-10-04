# DriftGuard-IoT

Leakage-safe intrusion detection and drift adaptation across IoT/IIoT.

[Source repository](https://github.com/Arungharami/DriftGuard-IoT) · [Portfolio index](../README.md)

## Current foundation

Development and synthetic runs are documented; real-data research campaign is blocked.

This roadmap was prepared from the repository README on October 4, 2026. It records proposed work, not completed experiments, production certification or a fresh test run. Resolve status disagreements against the project's authoritative artifacts before updating public claims.

## Materials to review

- [docs/datasets.md](https://github.com/Arungharami/DriftGuard-IoT/blob/HEAD/docs/datasets.md)
- [docs/scientific-protocol.md](https://github.com/Arungharami/DriftGuard-IoT/blob/HEAD/docs/scientific-protocol.md)
- [docs/m5-protocol.md](https://github.com/Arungharami/DriftGuard-IoT/blob/HEAD/docs/m5-protocol.md)
- [configs/](https://github.com/Arungharami/DriftGuard-IoT/tree/HEAD/configs/)

## Work packages

### 1. Establish authorized dataset manifests

**Priority:** P0 · **State:** Proposed; completion evidence required

Obtain approved TON_IoT, WUSTL-IIOT-2021 and EdgeIIoTset files without committing raw data.

**Acceptance criteria:** Acquisition terms, checksums, schema and availability are recorded; absent datasets remain blocked.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 2. Execute leakage-safe baselines

**Priority:** P1 · **State:** Proposed; completion evidence required

Depends on real-data manifests and fixed split policy.

**Acceptance criteria:** Reference baselines generate reportable run manifests, class metrics and leakage audit evidence.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

### 3. Evaluate drift and adaptation

**Priority:** P2 · **State:** Proposed; completion evidence required

Depends on accepted baselines. Compare static, periodic and drift-triggered policies.

**Acceptance criteria:** Chronological/domain evaluations include false alarms, minority classes, resource cost and uncertainty.

**Delivery record:** Link the issue, pull request, validation output and accepted artifact. If prerequisites are missing, record the blocker instead of a completion percentage.

## Board handoff

Create or reuse repository issues for these packages after checking for existing equivalent work. Add those issues to the matching board, set the real status, and attach the source materials above. Do not create duplicate boards merely to increase project count.
