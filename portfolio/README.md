# Research & Product Portfolio

A guide to the implementation, supporting materials and next deliverables across this portfolio. Project pages link to existing source materials and define three prioritized work packages with acceptance criteria.

**Reviewed:** October 4, 2026. Status descriptions summarize repository documentation; they are not independent certification or newly executed validation.

## Explore the work

| Project | Focus | Foundation and next work |
|---|---|---|
| [Drift-Robust TinyML](projects/Drift-Robust-TinyML-Research-System.md) | Electronic-nose learning under chronological sensor drift. | Research pipeline; physical MCU measurements remain unavailable. |
| [DriftCVE-NLP](projects/DriftCVE-NLP.md) | Temporal drift in vulnerability classification and retrieval. | README reports a published dataset and recorded model experiments; live inference is pending. |
| [Biomedical Hybrid IR](projects/biomedical-hybrid-ir.md) | Comparing lexical, dense, hybrid and reranked biomedical search. | README reports six NFCorpus systems; broader research validation remains next work. |
| [DriftGuard-IoT](projects/DriftGuard-IoT.md) | Leakage-safe intrusion detection and drift adaptation across IoT/IIoT. | Development and synthetic runs are documented; real-data research campaign is blocked. |
| [Customer Behavior Research — Part 2](projects/Customer-Behavior-Prediction-in-Banking-and-Insurance-2.md) | Temporal stability, calibration, explanation stability and operational value. | Protocol and preflight utilities exist; empirical manuscript results require authorized data and execution. |
| [Lead.AI Product Platform](projects/Lead-AI-product.md) | Lead capture and business automation across web and mobile. | Multi-platform MVP; payments, messaging and other production features remain incomplete. |
| [Lead.AI Labs Fraud Benchmark](projects/lead-ai-labs-hf-upgrade.md) | Reproducible tabular evaluation and controlled model/benchmark publishing. | Controlled synthetic reference benchmark; existing Gradio demonstration is rule based. |
| [SitaRam](projects/SitaRam.md) | Source-grounded Ramayana study with multilingual reading and assistance. | Flutter application and corpus gates exist; corpus coverage remains incomplete. |
| [Working Woman Report](projects/workingwomanreport.com.md) | Canonical weekly reporting with coordinated publishing and distribution. | Editorial rebuild with schemas and provider adapter foundations. |
| [FleetDesk](projects/FleetDesk.md) | Single-owner rental operations from two cars to a larger fleet. | Operational pilot with authenticated SQLite server and separate browser-only static demo. |
| [DailyOps](projects/dailyops-ai-agent.md) | Mobile planning for classes, research and work. | Browser-local calendar prototype with rule-based extraction; no cross-device calendar sync. |

## Active delivery trackers

These open coordination issues collect the 33 proposed work packages, materials and acceptance criteria. They do not imply board placement or completed implementation.

| Project | Tracking |
|---|---|
| Drift-Robust TinyML | [Open tracking issue](https://github.com/Arungharami/Arungharami/issues/4) |
| DriftCVE-NLP | [Open tracking issue](https://github.com/Arungharami/Arungharami/issues/5) |
| Biomedical Hybrid IR | [Open tracking issue](https://github.com/Arungharami/Arungharami/issues/6) |
| DriftGuard-IoT | [Open tracking issue](https://github.com/Arungharami/Arungharami/issues/7) |
| Customer Behavior Research — Part 2 | [Open tracking issue](https://github.com/Arungharami/Arungharami/issues/8) |
| Lead.AI Product Platform | [Open tracking issue](https://github.com/Arungharami/Arungharami/issues/9) |
| Lead.AI Labs Fraud Benchmark | [Open tracking issue](https://github.com/Arungharami/Arungharami/issues/10) |
| SitaRam | [Open tracking issue](https://github.com/Arungharami/Arungharami/issues/11) |
| Working Woman Report | [Open tracking issue](https://github.com/Arungharami/Arungharami/issues/12) |
| FleetDesk | [Open tracking issue](https://github.com/Arungharami/Arungharami/issues/13) |
| DailyOps | [Open tracking issue](https://github.com/Arungharami/Arungharami/issues/14) |

## How delivery is tracked

P0 addresses trust, data integrity or the core working flow. P1 establishes the next useful validated deliverable. P2 broadens evidence or prepares integration and release. A priority is not a deadline.

A work package is complete when its acceptance criteria pass and the issue links to its implementation and validation evidence. A synthetic run, a deployed interface and a physical measurement are different kinds of evidence and should be described explicitly.

## GitHub Projects setup

This repository provides roadmaps and materials. It does not imply that GitHub Projects boards have been created or populated.

Use one portfolio overview and reuse existing project-specific boards. The supplied [Project 9](https://github.com/users/Arungharami/projects/9) has not been inspected because browser access is blocked; confirm its title and purpose before assigning any repository to it.

Suggested fields:

| Field | Values or purpose |
|---|---|
| Status | Backlog, Ready, In progress, In review, Done, Blocked |
| Priority | P0, P1, P2 |
| Work type | Research, Data, Engineering, Documentation, Validation, Release |
| Repository | Link to the owning repository |
| Evidence | Link to accepted artifact, test run or reviewed document |
| Blocker | Specific missing input, dependency or access |
| Iteration | Assign only when a realistic execution window is agreed |

Suggested views: prioritized backlog sorted by priority; status board grouped by status; current iteration filtered to the selected iteration; roadmap using agreed target dates; bugs filtered by an existing bug label; my items filtered by actual assignee.

Before adding items, search existing issues and pull requests. Reuse equivalent work rather than creating duplicate tickets. Keep measured achievements, current work and future plans distinguishable. Retain existing board settings and useful views.
