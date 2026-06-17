# Portfolio Index

This index groups work by the kinds of systems I want reviewers to sample: evaluation harnesses, tool-using agents, robotics policies, model-behavior experiments, and high-stakes scientific ML pipelines.

## AI Security and Frontier Red Team

- **SpecGuard / SpecGuard-Chem** - agent evaluation contracts for structured rule-following, verifier use, abstention, action semantics, and tool-mediated decisions. Chemistry is the first typed verifier substrate; the core work is evaluation design.
- **[Fact Checker](https://github.com/danhussey/fact-checker)** - streaming claim extraction and verification from live speech, with noisy transcript handling, duplicate suppression, structured outputs, diagnostics, and an adversarial transcript eval scaffold.
- **[Transport NSW MCP](https://github.com/danhussey/transportnsw-mcp)** - Model Context Protocol interface for real-time transport data, useful as a small concrete tool-use surface.

## Reinforcement Learning and Agents

- **[ACT implementation](https://github.com/danhussey/act_implementation)** - readable Action Chunking Transformer implementation with robomimic data, image observations, closed-loop simulator rollouts, training curves, and rollout videos.
- **SpecGuard post-training playground** - toy environment for public task views, verifier calls, ACCEPT/REJECT/ABSTAIN actions, tool budgets, and deterministic reward from typed task contracts.

## Machine Learning Systems and Performance

- **Senvaro** - private repository; public demo/case study. Production medical scribe with browser recording, transcription, model-generated clinical notes, authentication, cloud deployment, observability, and testing.
- **[Fact Checker observability](https://github.com/danhussey/fact-checker)** - Sentry-backed client/server/edge diagnostics, masked replay, structured pipeline logs, feedback attachments, rate limiting, and transcript diagnostic controls.
- **SpecGuard artifact packaging** - cache/replay support, deterministic benchmark releases, anonymous artifact packaging, validation audits, and result table generation.

## Mechanistic Interpretability and Model Behavior

- **[code-pattern-brained](https://github.com/danhussey/code-pattern-brained)** - compact experiment around code-pattern associations and model behavior.
- **SpecGuard wrapper-saturation result** - a well-engineered wrapper saturating the test split is treated as an evaluation-validity result, not a model leaderboard win.

## Scientific Machine Learning

- **[Glioma Recurrence Risk Pipeline](https://github.com/danhussey/brain-cancer-recurrence)** - retrospective research pipeline for recurrence-risk modelling with patient-level splits, recurrence labels mapped to baseline space, leakage controls, calibration concerns, and human-readable QC reports.
- **[Connectomic Demo](https://github.com/danhussey/connectomic-demo)** - archival classical ML demo using ABIDE connectivity features, XGBoost, SHAP feature attribution, and cross-site generalisation analysis.

## Lower-Emphasis Public Repos

These can stay public if they have clear README status labels, but they should not dominate the pinned or profile story: AnkiOCR, htmx-gpt, cafe-song-selector, carsales-scraper, Advent-of-Code-2024, and Dotfiles.

## Visibility Review

Before relying on a repository as a public portfolio signal, confirm that an unauthenticated reviewer can access it. Private repositories can still be useful as work samples, demos, or case studies, but they should not be the only route to understanding the project.
