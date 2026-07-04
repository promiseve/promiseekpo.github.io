---
title: "REPAIR-Bench: A Benchmark for Robot Error Perception and Interaction Recovery"
collection: publications
permalink: /publication/2026-05-01-repair-bench
excerpt: 'A benchmark of 214 human-robot interaction trials from 41 participants with synchronized multimodal signals (facial action units, head pose, speech, and post-interaction affect), formalizing three novel evaluation tasks across the full failure lifecycle. Hierarchical recurrent modeling improves failure detection over single-session baselines (strict F1: 0.80 vs. 0.68).'
date: 2026-05-01
venue: 'Submitted to IROS 2026'
citation: 'G. Pioldi, Y. Batra, Y. Bai, P. Marur, A. Ibrayeva, <b>Promise Ekpo</b>, A. Taylor. "REPAIR-Bench: A Benchmark for Robot Error Perception and Interaction Recovery." Submitted to IROS, 2026.'
---
A benchmark built on 214 interaction trials from 41 participants, spanning four induced failure types with synchronized multimodal signals: facial action units (OpenFace), head pose, speech transcripts, and post-interaction affect and recovery reports. We formalize three novel evaluation tasks capturing the full failure lifecycle: longitudinal failure detection across interdependent sessions, visual failure-type classification, and user-centered recovery-preference prediction. Hierarchical recurrent modeling improves failure detection over single-session baselines (strict F1: 0.80 vs. 0.68), with failure-localization median absolute error of 2.97s. We fine-tune Mistral-7B with QLoRA for recovery prediction (Hit@5 = 0.76, F1@5 = 0.32).
