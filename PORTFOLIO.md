# Portfolio Index

The projects below are organized by the evidence they provide: experimental design, scientific-software judgment, closed-loop evaluation, and production engineering.

## Scientific and machine-learning research

### [Constrained Compound Prioritization: Compliance vs. Utility](https://github.com/danhussey/specguard_chem_v2)

A 50-card CARA/ChEMBL audit that separates rule compliance from hidden retrospective utility. The repository includes frozen decision cards, RDKit validators, random/rule/similarity/QSAR/LLM baselines, replay controls, bootstrap comparisons, and public result artifacts.

**Finding:** guarded systems achieved full post-repair compliance and beat rule/similarity baselines, while linear SVR remained stronger by 3.19 feasible-utility points (95% CI 1.94–4.69). [Read the result snapshot.](https://github.com/danhussey/specguard_chem_v2/blob/main/paper/CARA_LO_PAPER_50_RESULTS.md)

### [Endpoint-Gradient Subspaces in Language Models](https://github.com/danhussey/endpoint-spaces)

A controlled mechanistic-interpretability pilot fitting SVD subspaces to endpoint gradients across 13 behavioral families. It uses held-out projection energy, rank-matched random controls, rank sweeps, bootstrap intervals, and GPT-2/Qwen comparison.

**Finding:** endpoint-defined subspaces were common; the broad claim that J-space is uniquely low-rank weakened under endpoint-definition controls and cross-model comparison. [Read the accessible report.](https://github.com/danhussey/endpoint-spaces/blob/main/docs/is-j-space-special.md)

### [Voxelwise Glioma Recurrence Modeling from MRI](https://github.com/danhussey/brain-cancer-recurrence)

A retrospective MRI pipeline with longitudinal label registration, patient-level splitting, leakage guards, baseline models, calibration metrics, and human-readable QC reports.

**Finding:** on 12 held-out cases, voxel logistic regression trailed a simple tumor-distance baseline (AUPRC 0.203 vs. 0.264), an important negative result for the current feature set. [Read the completed evaluation.](https://github.com/danhussey/brain-cancer-recurrence/blob/main/docs/exec-plans/completed/ucsd-clinical-controls-evaluation.md)

### [Action Chunking for Closed-Loop Robot Imitation](https://github.com/danhussey/act_implementation)

A readable PyTorch implementation of Action Chunking Transformer policies with state and image encoders, checkpointing, robomimic demonstrations, robosuite rollouts, video, and metric logging.

**Finding:** final checkpoints reached 18/20 Can and 17/20 vision-Lift successes, compared with 7/20 and 13/20 for validation-loss-selected checkpoints in the reported pilots.

### [Raman Spectral Triage for Neuro-Oncology Drugs](https://github.com/danhussey/raman-feasability)

An auditable Python CLI and reporting pipeline for screening whether drug spectra are plausibly separable from paraffin and tissue-like backgrounds before wet-lab experiments. It includes metadata validation, preprocessing, peak-collision and spectral-angle metrics, NNLS recovery simulation, and explicit scientific limits.

**Finding:** the first-pass public-spectrum screen prioritized temozolomide for controlled spike-in testing; several other candidates remained blocked by weak reference spectra.

## Evaluation frameworks

- **[Model Rule-Following with Verifier Access](https://github.com/danhussey/specguard-agent)** — Machine-checkable task contracts for rule-following, accept/reject/abstain decisions, verifier-tool use, explicit budgets, cache/replay, and wrapper-saturation analysis.
- **[Fact Checker](https://github.com/danhussey/fact-checker)** — Streaming claim extraction and verification from noisy speech, with structured outputs, diagnostics, rate limiting, and an offline adversarial-transcript scaffold.
- **[Transport NSW MCP](https://github.com/danhussey/transportnsw-mcp)** — A small, concrete tool-use surface for real-time public-transport data.

## Production systems

- **[Senvaro](https://senvaro.com/demo)** — Private clinical-documentation system with browser recording, local or Australia-hosted speech/note generation, authentication, audit trails, observability, and automated testing.
- **Professional forecasting and data systems** — Multi-horizon ticket-demand forecasting, Azure/Databricks data pipelines, reporting systems, and retrieval-grounded LLM implementation work.

## Archival work

Older utilities, coursework, and exploratory applications remain available in the repository list but are intentionally excluded from the main research-engineering portfolio.
