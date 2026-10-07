# Public Repository Audit and Delivery Tracker

Reviewed October 6, 2026 (America/New_York).

## Scope and findings

GitHub public-repository search returned **46 public repositories** for Arungharami. Root README.md was retrieved in **36**; **10** returned not found. This is a documentation and visibility audit, not an independent validation of every application or research result. Alternate README filenames may exist where README.md was not found.

The public profile now features public applications. Private source repositories are excluded from public pin recommendations. Repository visibility was not changed.

## Prepared improvements

The following pull requests are **drafts, not merged**. Each adds a project-specific starting point and contribution guidance. Existing contributor policies are retained. Final diffs were checked: only README.md and CONTRIBUTING.md changed, plus the biomedical educational example; no existing lines were deleted.

| Project | Reviewable change | State |
|---|---|---|
| [biomedical-hybrid-ir](https://github.com/Arungharami/biomedical-hybrid-ir) | [PR #2](https://github.com/Arungharami/biomedical-hybrid-ir/pull/2) | Draft; merge and complete CI verification pending |
| [DriftCVE-NLP](https://github.com/Arungharami/DriftCVE-NLP) | [PR #13](https://github.com/Arungharami/DriftCVE-NLP/pull/13) | Draft; merge and complete CI verification pending |
| [Drift-Robust-TinyML-Research-System](https://github.com/Arungharami/Drift-Robust-TinyML-Research-System) | [PR #25](https://github.com/Arungharami/Drift-Robust-TinyML-Research-System/pull/25) | Draft; merge and complete CI verification pending |
| [DriftGuard-IoT](https://github.com/Arungharami/DriftGuard-IoT) | [PR #38](https://github.com/Arungharami/DriftGuard-IoT/pull/38) | Draft; merge and complete CI verification pending |
| [Lead-AI-product](https://github.com/Arungharami/Lead-AI-product) | [PR #9](https://github.com/Arungharami/Lead-AI-product/pull/9) | Draft; merge and complete CI verification pending |
| [lead-ai-labs-hf-upgrade](https://github.com/Arungharami/lead-ai-labs-hf-upgrade) | [PR #16](https://github.com/Arungharami/lead-ai-labs-hf-upgrade/pull/16) | Draft; merge and complete CI verification pending |
| [SitaRam](https://github.com/Arungharami/SitaRam) | [PR #9](https://github.com/Arungharami/SitaRam/pull/9) | Draft; merge and complete CI verification pending |
| [Java_script_0-hero](https://github.com/Arungharami/Java_script_0-hero) | [PR #3](https://github.com/Arungharami/Java_script_0-hero/pull/3) | Draft; merge and complete CI verification pending |
| [workingwomanreport.com](https://github.com/Arungharami/workingwomanreport.com) | [PR #4](https://github.com/Arungharami/workingwomanreport.com/pull/4) | Draft; merge and complete CI verification pending |
| [Customer-Behavior-Prediction-in-Banking-and-Insurance-2](https://github.com/Arungharami/Customer-Behavior-Prediction-in-Banking-and-Insurance-2) | [PR #8](https://github.com/Arungharami/Customer-Behavior-Prediction-in-Banking-and-Insurance-2/pull/8) | Draft; merge and complete CI verification pending |

## Executed verification

Biomedical Hybrid IR:
- Source modules retrieved from the default branch; TF-IDF example ran locally using Python 3.12.14, NumPy 2.3.5, scikit-learn 1.8.0.
- `PYTHONPATH=src python examples/tfidf_quickstart.py`: completed. "dietary fiber" ranked the hand-written nutrition document first, score 0.534522.
- `PYTHONPATH=src python -m unittest discover -s tests -p test_missing_query_regressions.py -v`: **2 tests passed**.
- These are educational/API and regression checks, not a new NFCorpus experiment.
- Clean dependency installation, full pytest suite, benchmark downloads, transformer experiments, and production builds: **NOT_RUN**. Required dependencies and external downloads are unavailable in the current workspace.

All ten PR diffs were checked for scope and preservation of existing content. New repository file links were checked against source trees or successful file reads. This does not verify deployed portal availability.

## Complete public inventory

The table records a specific next action for every public repository returned by search. README presence and length do not establish code quality. Items not in the ten PRs were audited, not edited.

| Repository | Default branch | Root README.md | Next action |
|---|---|---|---|
| [Amazon_product_search](https://github.com/Arungharami/Amazon_product_search) | `main` | Retrieved | Document purpose, runnable setup, and one verified example |
| [Arungharami](https://github.com/Arungharami/Arungharami) | `main` | Retrieved | Profile updated; maintain audit and measure reach |
| [banking-insurance-customer-ai](https://github.com/Arungharami/banking-insurance-customer-ai) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [biomedical-hybrid-ir](https://github.com/Arungharami/biomedical-hybrid-ir) | `main` | Retrieved | Review prepared visitor/contributor change |
| [Book_web](https://github.com/Arungharami/Book_web) | `main` | Not found | Inspect source and document purpose/setup; README.md was not found |
| [Capstone-Project-Potential](https://github.com/Arungharami/Capstone-Project-Potential) | `master` | Retrieved | Document purpose, runnable setup, and one verified example |
| [class2career-ai](https://github.com/Arungharami/class2career-ai) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [Customer-Behavior-Prediction-in-Banking-and-Insurance-2](https://github.com/Arungharami/Customer-Behavior-Prediction-in-Banking-and-Insurance-2) | `main` | Retrieved | Review prepared visitor/contributor change |
| [Division-Construction](https://github.com/Arungharami/Division-Construction) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [docs](https://github.com/Arungharami/docs) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [Drift-Robust-TinyML-Research-System](https://github.com/Arungharami/Drift-Robust-TinyML-Research-System) | `main` | Retrieved | Review prepared visitor/contributor change |
| [DriftCVE-NLP](https://github.com/Arungharami/DriftCVE-NLP) | `research/full-platform` | Retrieved | Review prepared visitor/contributor change |
| [DriftGuard-IoT](https://github.com/Arungharami/DriftGuard-IoT) | `main` | Retrieved | Review prepared visitor/contributor change |
| [ecomarce_1.24.2025](https://github.com/Arungharami/ecomarce_1.24.2025) | `main` | Not found | Inspect source and document purpose/setup; README.md was not found |
| [financial-hybrid-ir](https://github.com/Arungharami/financial-hybrid-ir) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [Game_Challenge_Handshake](https://github.com/Arungharami/Game_Challenge_Handshake) | `main` | Retrieved | Document purpose, runnable setup, and one verified example |
| [GigFinanceAI](https://github.com/Arungharami/GigFinanceAI) | `main` | Not found | Inspect source and document purpose/setup; README.md was not found |
| [Hugging-Face-Core-Development-Lab.](https://github.com/Arungharami/Hugging-Face-Core-Development-Lab.) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [hydrogen-template](https://github.com/Arungharami/hydrogen-template) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [Java_script_0-hero](https://github.com/Arungharami/Java_script_0-hero) | `main` | Retrieved | Review prepared visitor/contributor change |
| [keylo-ai-companion](https://github.com/Arungharami/keylo-ai-companion) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [Keylo.ai](https://github.com/Arungharami/Keylo.ai) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [lead-ai-fraud-shield](https://github.com/Arungharami/lead-ai-fraud-shield) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [Lead-ai-gumroad-products](https://github.com/Arungharami/Lead-ai-gumroad-products) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [lead-ai-hf-portfolio](https://github.com/Arungharami/lead-ai-hf-portfolio) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [lead-ai-labs-hf-upgrade](https://github.com/Arungharami/lead-ai-labs-hf-upgrade) | `main` | Retrieved | Review prepared visitor/contributor change |
| [Lead-AI-product](https://github.com/Arungharami/Lead-AI-product) | `main` | Retrieved | Review prepared visitor/contributor change |
| [Lead-AI-US-C2C](https://github.com/Arungharami/Lead-AI-US-C2C) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [Lead.ai_gumroad](https://github.com/Arungharami/Lead.ai_gumroad) | `main` | Not found | Inspect source and document purpose/setup; README.md was not found |
| [Lead.ai-model-huginface](https://github.com/Arungharami/Lead.ai-model-huginface) | `main` | Not found | Inspect source and document purpose/setup; README.md was not found |
| [LSTM-V.03](https://github.com/Arungharami/LSTM-V.03) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [Nargis-Tanjiman-Ara-Digital-Legacy](https://github.com/Arungharami/Nargis-Tanjiman-Ara-Digital-Legacy) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [Payment-Management-app](https://github.com/Arungharami/Payment-Management-app) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [pharmacy-assistant](https://github.com/Arungharami/pharmacy-assistant) | `master` | Retrieved | Reproduce one documented workflow before broader promotion |
| [Project_M](https://github.com/Arungharami/Project_M) | `master` | Not found | Inspect source and document purpose/setup; README.md was not found |
| [Project_management-](https://github.com/Arungharami/Project_management-) | `main` | Not found | Inspect source and document purpose/setup; README.md was not found |
| [QA-project-card-transaction](https://github.com/Arungharami/QA-project-card-transaction) | `main` | Retrieved | Document purpose, runnable setup, and one verified example |
| [SauceDemoTest](https://github.com/Arungharami/SauceDemoTest) | `main` | Not found | Inspect source and document purpose/setup; README.md was not found |
| [seleniam_add_level](https://github.com/Arungharami/seleniam_add_level) | `main` | Not found | Inspect source and document purpose/setup; README.md was not found |
| [Seleniam_test_hr](https://github.com/Arungharami/Seleniam_test_hr) | `main` | Not found | Inspect source and document purpose/setup; README.md was not found |
| [SitaRam](https://github.com/Arungharami/SitaRam) | `main` | Retrieved | Review prepared visitor/contributor change |
| [Smart-Finance-AI](https://github.com/Arungharami/Smart-Finance-AI) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [Tic-TacAuto-Agent](https://github.com/Arungharami/Tic-TacAuto-Agent) | `main` | Retrieved | Document purpose, runnable setup, and one verified example |
| [Trustworthy-TinyML-IoT-Security](https://github.com/Arungharami/Trustworthy-TinyML-IoT-Security) | `feat/research-foundation` | Retrieved | Document purpose, runnable setup, and one verified example |
| [v0.5-fraud-detection-platform](https://github.com/Arungharami/v0.5-fraud-detection-platform) | `main` | Retrieved | Reproduce one documented workflow before broader promotion |
| [workingwomanreport.com](https://github.com/Arungharami/workingwomanreport.com) | `main` | Retrieved | Review prepared visitor/contributor change |

## Work order

1. Review the three flagship PRs and their actual check results. Merge only under each repository's existing workflow.
2. Complete a clean-environment NFCorpus baseline reproduction before advertising benchmark reproduction as newly verified.
3. Work through the remaining application PRs and verify one complete user workflow per application.
4. Inspect the ten repositories without root README.md and the short legacy READMEs. Establish their actual purpose and runnable behavior before authoring documentation. Do not invent implementations or metrics, or create filler content.
5. Record repository Traffic snapshots before selected release sharing. Outside usage, reproduction reports, and useful contributions complement follower counts.

## Remaining boundaries

Profile pins are recommended, not changed. Public demo videos and outreach have not been created or sent. Private repositories remain private. These changes do not certify production readiness, publication readiness, model validity, or physical hardware performance.

[Portfolio navigator](README.md) · [Profile growth plan](PROFILE_GROWTH_PLAN.md)
