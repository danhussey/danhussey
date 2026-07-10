# Daniel Hussey

Machine learning and scientific software engineer, and medical student in Sydney.

I build reproducible ML benchmarks and research pipelines across molecular decision-making, language-model internals, robotics, and neuroimaging. I care about strong baselines, leakage control, held-out evaluation, and reporting results that survive contact with the controls.

## Selected research and engineering

1. **[Constrained Compound Prioritization: Compliance vs. Utility](https://github.com/danhussey/specguard_chem_v2/blob/main/paper/CARA_LO_PAPER_50_RESULTS.md)** — Built a 50-card CARA/ChEMBL benchmark with RDKit validation, QSAR/LLM baselines, replayable runs, and paired-bootstrap comparisons. Guarded systems reached full post-repair compliance, but linear SVR remained stronger by 3.19 feasible-utility points (95% CI 1.94–4.69).
2. **[Endpoint-Gradient Subspaces in Language Models](https://github.com/danhussey/endpoint-spaces/blob/main/docs/is-j-space-special.md)** — Fit and compared subspaces across 13 behavioral endpoint families using held-out projection energy, rank-matched controls, rank sweeps, and bootstrap intervals. GPT-2 and Qwen pilots weakened the hypothesis that J-space is uniquely low-rank.
3. **[Voxelwise Glioma Recurrence Modeling from MRI](https://github.com/danhussey/brain-cancer-recurrence/blob/main/docs/exec-plans/completed/ucsd-clinical-controls-evaluation.md)** — Built a longitudinal MRI pipeline over 136 complete subjects, curating 37 eligible cases with patient-level splits and leakage guards. On 12 held-out cases, voxel logistic regression trailed a tumor-distance baseline (AUPRC 0.203 vs. 0.264).
4. **[Action Chunking for Closed-Loop Robot Imitation](https://github.com/danhussey/act_implementation)** — Implemented state- and image-based ACT policies with robosuite rollouts; final checkpoints reached 18/20 Can and 17/20 vision-Lift successes, exposing validation loss as a poor policy selector in these pilots.
5. **[Raman Spectral Triage for Neuro-Oncology Drugs](https://github.com/danhussey/raman-feasability)** — Built an auditable signal-processing pipeline for screening drug/matrix spectral separability; the first-pass analysis prioritized temozolomide for controlled spike-in testing while flagging the limits of digitized public spectra.

The longer [portfolio index](PORTFOLIO.md) includes evaluation frameworks and production systems.

## Production systems

- **[Senvaro](https://senvaro.com/demo)** — Privacy-first clinical documentation with browser recording, local or Australia-hosted transcription and note generation, authentication, audit trails, observability, and end-to-end testing. The repository is private.
- **[Fact Checker](https://github.com/danhussey/fact-checker)** — Real-time claim extraction and verification for noisy live speech, with structured outputs, duplicate suppression, diagnostics, and an offline evaluation scaffold.

## Writing

- [Lumine: How a 7B Model Plays Genshin Impact for 5 Hours](https://danhussey.bearblog.dev/lumine-how-a-7b-model-plays-genshin-impact-for-5-hours/)
- [Craftsmanship, per Million Tokens](https://danhussey.bearblog.dev/craftsmanship-per-million-tokens/)
- [Debugging the ChatGPT Mac App's Keyboard Input Lag](https://danhussey.bearblog.dev/debugging-the-chatgpt-mac-apps-keyboard-input-lag/)

## Elsewhere

[Website](https://danielrhussey.com) / [Blog](https://danhussey.bearblog.dev/blog/) / [Email](mailto:daniel.r.hussey@gmail.com)
