# Portfolio Index

This index groups work by the kinds of systems I want reviewers to sample: evaluation harnesses, tool-using agents, robotics policies, model-behavior experiments, and high-stakes scientific ML pipelines.

## AI Security and Frontier Red Team

- **[SpecGuard](https://github.com/danhussey/specguard-agent)** - agent evaluation contracts for structured rule-following, verifier use, abstention, action semantics, and tool-mediated decisions. Chemistry is the first typed verifier substrate; the core work is evaluation design.
- **[SpecGuard-Chem v2](https://github.com/danhussey/specguard_chem_v2)** - constrained compound-prioritisation audit separating rule compliance from hidden retrospective utility on frozen CARA decision cards.
- **[Fact Checker](https://github.com/danhussey/fact-checker)** - streaming claim extraction and verification from live speech, with noisy transcript handling, duplicate suppression, structured outputs, diagnostics, and an adversarial transcript eval scaffold.
- **[Transport NSW MCP](https://github.com/danhussey/transportnsw-mcp)** - Model Context Protocol interface for real-time transport data, useful as a small concrete tool-use surface.

## Reinforcement Learning and Agents

- **[ACT implementation](https://github.com/danhussey/act_implementation)** - readable Action Chunking Transformer implementation with robomimic data, image observations, closed-loop simulator rollouts, training curves, and rollout videos.
- **[SpecGuard post-training playground](https://github.com/danhussey/specguard-agent/blob/main/docs/design-docs/posttraining-playground.md)** - toy environment for public task views, verifier calls, ACCEPT/REJECT/ABSTAIN actions, tool budgets, and deterministic reward from typed task contracts.

## Machine Learning Systems and Performance

- **Senvaro** - private repository; public demo/case study. Production medical scribe with browser recording, transcription, model-generated clinical notes, authentication, cloud deployment, observability, and testing.
- **[Fact Checker observability](https://github.com/danhussey/fact-checker)** - Sentry-backed client/server/edge diagnostics, masked replay, structured pipeline logs, feedback attachments, rate limiting, and transcript diagnostic controls.
- **[SpecGuard artifact packaging](https://github.com/danhussey/specguard-agent)** - cache/replay support, deterministic benchmark releases, anonymous artifact packaging, validation audits, and result table generation.

## Mechanistic Interpretability and Model Behavior

- **[code-pattern-brained](https://github.com/danhussey/code-pattern-brained)** - compact experiment around code-pattern associations and model behavior.
- **[SpecGuard wrapper-saturation result](https://github.com/danhussey/specguard-agent/blob/main/REVIEWER_GUIDE.md)** - a well-engineered wrapper saturating the test split is treated as an evaluation-validity result, not a model leaderboard win.

## Scientific Machine Learning

- **[Glioma Recurrence Risk Pipeline](https://github.com/danhussey/brain-cancer-recurrence)** - retrospective research pipeline for recurrence-risk modelling with patient-level splits, recurrence labels mapped to baseline space, leakage controls, calibration concerns, and human-readable QC reports.
- **[Raman Spectral-Geometry Triage](https://github.com/danhussey/raman-feasability)** - reproducible Python CLI and static-report pipeline for screening whether neuro-oncology drug Raman spectra are plausibly separable from paraffin and brain/tumour-like background spectra, with metadata validation, preprocessing, peak-collision scoring, NNLS recovery simulation, and cautious go/no-go reporting.
- **[Connectomic Demo](https://github.com/danhussey/connectomic-demo)** - archival classical ML demo using ABIDE connectivity features, XGBoost, SHAP feature attribution, and cross-site generalisation analysis.

## Archival and Utility Repos

Older utility projects and archival coursework are intentionally not part of the
main portfolio. The projects above are the best samples for research-engineering
review.
